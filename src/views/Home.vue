<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <forms msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import forms from "@/components/forms.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    forms,
  },
};
</script>
