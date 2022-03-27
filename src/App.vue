/* eslint-disable no-unused-vars */
<template>
  <div id="nav">
    <nav>
      <div class="logo">Mpiloenviroservices</div>
      <input type="checkbox" id="click" />
      <label for="click" class="menu-btn">
        <i class="fas fa-bars"></i>
      </label>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
        <li><router-link to="/service">Service</router-link></li>
        <li><router-link to="/project">Project</router-link></li>
        <li><router-link to="/contact">Contact</router-link></li>
      </ul>
    </nav>
  </div>
  <router-view />
  <a @click="scrollTop" v-show="visible" class="bottom-right">
    <slot></slot>
  </a>
</template>

<script>
import { ref } from "vue";

export default {
  setup() {
    let showMenu = ref(false);
    const toggleNav = () => (showMenu.value = !showMenu.value);
    return { showMenu, toggleNav };
  },
};
</script>

<style lang="css">
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
body {
  background-color: linear-gradient(
    #051937,
    #004d7a,
    #008793,
    #00bf72,
    #a8eb12
  );
}
nav {
  display: flex;
  height: 80px;
  width: 100%;
  background: #22543d;
  align-items: center;
  justify-content: space-between;
  padding: 0 50px 0 100px;
  flex-wrap: wrap;
}
nav .logo {
  color: #fff;
  font-size: 20px;
  font-weight: 400;
}
nav ul {
  display: flex;
  flex-wrap: wrap;
  list-style: none;
}
nav ul li {
  margin: 0 5px;
}
nav ul li a {
  color: #f2f2f2;
  text-decoration: none;
  font-size: 14px;
  font-weight: 500;
  padding: 8px 15px;
  border-radius: 5px;
  letter-spacing: 1px;
  transition: all 0.3s ease;
}
nav ul li a.active,
nav ul li a:hover {
  color: #111;
  background: #fff;
}
nav .menu-btn i {
  color: #fff;
  font-size: 22px;
  cursor: pointer;
  display: none;
}
input[type="checkbox"] {
  display: none;
}
@media (max-width: 1000px) {
  nav {
    padding: 0 40px 0 50px;
  }
}
@media (max-width: 920px) {
  nav .menu-btn i {
    display: block;
  }
  #click:checked ~ .menu-btn i:before {
    content: "\f00d";
  }
  nav ul {
    position: absolute;
    top: 80px;
    left: -100%;
    background: #22543d;
    height: 70vh;
    width: 100%;
    text-align: center;
    display: block;
    transition: all 0.3s ease;
    z-index: 100;
  }
  #click:checked ~ ul {
    left: 0;
  }
  nav ul li {
    width: 100%;
    margin: 40px 0;
  }
  nav ul li a {
    width: 100%;
    margin-left: -100%;
    display: block;
    font-size: 13px;
    transition: 0.6s cubic-bezier(0.68, -0.55, 0.265, 1.55);
  }
  #click:checked ~ ul li a {
    margin-left: 0px;
  }
  nav ul li a.active,
  nav ul li a:hover {
    background: none;
    color: rgb(16, 216, 9);
  }
}
.content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  z-index: -1;
  width: 100%;
  padding: 0 30px;
  color: #1b1b1b;
}
.content div {
  font-size: 40px;
  font-weight: 700;
}
</style>
