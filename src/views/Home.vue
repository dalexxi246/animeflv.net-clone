<template>
  <template-with-main-nav-bar></template-with-main-nav-bar>
</template>

<script>
// @ is an alias to /src
import TemplateWithMainNavBar from "../components/templates/TemplateWithMainNavBar.vue";

export default {
  name: "Home",
  components: { TemplateWithMainNavBar },
};
</script>
