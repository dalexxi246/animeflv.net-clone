<template>
  <div>
    <organism-navigation-bar />
    <div class="container mt-3">
      <b-row>
        <b-col cols="4"><organism-sidebar /></b-col>
        <b-col cols="8"><organism-latest-episodes /></b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
import OrganismLatestEpisodes from "../organisms/OrganismLatestEpisodes.vue";
import OrganismNavigationBar from "../organisms/OrganismNavigationBar.vue";
import OrganismSidebar from "../organisms/OrganismSidebar.vue";

export default {
  components: {
    OrganismNavigationBar,
    OrganismSidebar,
    OrganismLatestEpisodes,
  },
  name: "TemplateWithMainNavBar",
};
</script>

<style scoped>
</style>