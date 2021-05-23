<template>
  <div>
    <organism-navigation-bar />
    <div class="container mt-3">
      <b-row>
        <b-col cols="3"><organism-sidebar /></b-col>
        <b-col cols="9">Main</b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
import OrganismNavigationBar from "../organisms/OrganismNavigationBar.vue";
import OrganismSidebar from "../organisms/OrganismSidebar.vue";

export default {
  components: { OrganismNavigationBar, OrganismSidebar },
  name: "TemplateWithMainNavBar",
};
</script>

<style scoped>
</style>