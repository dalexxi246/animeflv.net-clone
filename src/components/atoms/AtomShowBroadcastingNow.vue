<template>
  <div class="row" id="atom-show-broadcasting-now">
    <img src="play_icon_withing_circle" alt="play_icon_withing_circle" />
    <span>{{ name }}</span>
    <span>{{ showType }}</span>
  </div>
</template>

<script>
export default {
  props: ["name", "showType"],
};
</script>

<style>
</style>