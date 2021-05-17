<template>
  <b-navbar class="navbar container">
    <b-navbar-brand>
      <atom-logo class="navbar-brand" />
    </b-navbar-brand>
    <b-navbar-nav class="ml-auto">
      <b-nav-item class="my-auto"><molecule-navigation-bar-options /></b-nav-item>
      <b-nav-item class="my-auto"><atom-search-input /></b-nav-item>
      <b-nav-item class="my-auto"><atom-login-button /></b-nav-item>
      <b-nav-item class="my-auto"><atom-facebook-login-button /></b-nav-item>
    </b-navbar-nav>
  </b-navbar>
</template>

<script>
import AtomFacebookLoginButton from '../atoms/AtomFacebookLoginButton.vue';
import AtomHeaderLink from "../atoms/AtomHeaderLink.vue";
import AtomLoginButton from '../atoms/AtomLoginButton.vue';
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
    AtomLoginButton,
    AtomFacebookLoginButton,
  },
};
</script>

<style scoped>
</style>