<template>
  <div class="project">
    <Projectpage msg="Welcome to Your Vue.js App" />
    <forms msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import Projectpage from "@/components/Projectpage.vue";
import forms from "@/components/forms.vue";

export default {
  name: "project",
  components: {
    Projectpage,
    forms,
  },
};
</script>
