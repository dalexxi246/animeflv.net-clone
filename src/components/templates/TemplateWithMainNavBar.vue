<template>
  <div class="container-fluid">
    <organism-navigation-bar/>
  </div>
</template>

<script>
import OrganismNavigationBar from "../organisms/OrganismNavigationBar.vue";

export default {
  components: {OrganismNavigationBar},
  name: "TemplateWithMainNavBar",
};
</script>

<style scoped>
.container-fluid {
  background: #303439;
}
</style>