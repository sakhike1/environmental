<template>
  <div class="contact">
    <Contactpage msg="Welcome to Your Vue.js App" />
    <forms msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import Contactpage from "@/components/Contactpage.vue";
import forms from "@/components/forms.vue";

export default {
  name: "contact",
  components: {
    Contactpage,
    forms,
  },
};
</script>
