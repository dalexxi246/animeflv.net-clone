<template>
  <router-link :to="to">{{ name }}</router-link>
</template>

<script>
export default {
  name: "AtomHeaderLink",
  props: ['name', 'to'],
};
</script>

<style scoped>
a {
  text-decoration: none;
  text-transform: uppercase;
  font-weight: 700;
  font-size: 15px;
  color: rgb(146, 146, 146);
}

/* mouse over link */
a:hover {
  color: white;
}

</style>