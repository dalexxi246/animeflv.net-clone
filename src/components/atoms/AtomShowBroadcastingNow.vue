<template>
  <div class="container-fluid row text-nowrap my-2">
    <b-icon icon="play-circle-fill" class="col-3" />
    <span class="col-6 text-start">{{ name }}</span>
    <span
      class="
        col-3
        badge
        rounded-pill
        bg-primary
        fw-bolder
        text-white text-capitalize
        align-middle
      "
      >{{ showType }}</span
    >
  </div>
</template>

<script>
export default {
  props: ["name", "showType"],
};
</script>

<style scoped>
</style>