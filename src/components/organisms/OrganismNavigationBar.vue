<template>
  <b-navbar class="navbar container">
    <b-navbar-brand>
      <atom-logo class="navbar-brand" />
    </b-navbar-brand>
    <b-navbar-nav class="ml-auto">
      <b-nav-item><molecule-navigation-bar-options /></b-nav-item>
      <b-nav-item><atom-search-input /></b-nav-item>
    </b-navbar-nav>
  </b-navbar>
</template>

<script>
import AtomHeaderLink from "../atoms/AtomHeaderLink.vue";
import AtomLogo from "../atoms/AtomLogo.vue";
import AtomSearchInput from "../atoms/AtomSearchInput.vue";
import MoleculeNavigationBarOptions from "../molecules/MoleculeNavigationBarOptions.vue";

export default {
  name: "OrganismNavBar",
  components: {
    AtomHeaderLink,
    AtomLogo,
    MoleculeNavigationBarOptions,
    AtomSearchInput,
  },
};
</script>

<style scoped>
</style>