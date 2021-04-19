<template>
  <b-nav-form>
    <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
    <b-button size="sm" class="my-2 my-sm-0" type="submit">
      <i class="fas fa-camera"></i>
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
</style>