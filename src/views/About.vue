<template>
  <div class="about">
    <aboutpage msg="Welcome to Your Vue.js App" />
    <forms msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import Aboutpage from "@/components/aboutpage.vue";

export default {
  name: "about",
  components: {
    Aboutpage,
  },
};
</script>
