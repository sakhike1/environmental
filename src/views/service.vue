<template>
  <div class="service">
    <ServicePage msg="Welcome to Your Vue.js App" />
    <forms msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import ServicePage from "@/components/ServicePage.vue";
import forms from "@/components/forms.vue";

export default {
  name: "service",
  components: {
    ServicePage,
    forms,
  },
};
</script>
