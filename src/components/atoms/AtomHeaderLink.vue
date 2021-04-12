<template>
  <router-link :to="to"><span>{{ name }}</span></router-link>
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
    font-weight: bold;
    font-size: 15px;
}

/* unvisited link */
a:link {
  color: rgb(146, 146, 146);
}

/* mouse over link */
a:hover {
  color: white;
}

</style>