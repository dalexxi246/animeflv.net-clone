<template>
  <ul>
    <li><atom-header-link :name="'Inicio'" :to="'/'" /></li>
    <li><atom-header-link :name="'Directorio Anime'" :to="'/directorio'" /></li>
  </ul>
</template>

<script>
import AtomHeaderLink from "../atoms/AtomHeaderLink.vue";
export default {
  name: "MoleculeNavigationBarOptions",
  components: { AtomHeaderLink },
};
</script>

<style scoped>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
li {
  display: inline;
  padding: 12px;
}
</style>