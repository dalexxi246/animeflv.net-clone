<template>
  <nav class="navbar container">
    <div>
      <atom-logo class="navbar-brand"/>
    </div>
    <div>
      <molecule-navigation-bar-options />
    </div>
  </nav>
</template>

<script>
import AtomHeaderLink from "../atoms/AtomHeaderLink.vue";
import AtomLogo from "../atoms/AtomLogo.vue";
import MoleculeNavigationBarOptions from "../molecules/MoleculeNavigationBarOptions.vue";

export default {
  name: "OrganismNavBar",
  components: { AtomHeaderLink, AtomLogo, MoleculeNavigationBarOptions },
};
</script>

<style scoped>
</style>