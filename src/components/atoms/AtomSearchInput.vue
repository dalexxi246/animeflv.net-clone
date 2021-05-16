<template>
  <b-nav-form>
    <b-form-input size="sm" class="mr-sm-2" placeholder="Buscar" />
    <b-button size="sm" class="my-2 my-sm-0" type="submit">
      <b-icon icon="search" variant="light"/>
    </b-button>
  </b-nav-form>
</template>

<script>
export default {
  name: "AtomSearchInput",
  data() {
    return {
      text: "",
    };
  },
};
</script>

<style scoped>
button {
  background: none;
  border: none;
}
input {
  background: none;
  border: none;
  color: white;
}
input:focus {
  background: none;
  border: none;
  color: white;
}
input::placeholder {
  color: white;
}
form {
  border-radius: 25px;
  background: #252a2e;
  padding: 2px 8px;
}
</style>