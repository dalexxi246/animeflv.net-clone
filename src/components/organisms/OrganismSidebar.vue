<template>
  <div>
    <atom-lateral-image />
    <atom-lateral-facebook-follow-image class="mt-3"/>
  </div>
</template>

<script>
import AtomLateralFacebookFollowImage from "../atoms/AtomLateralFacebookFollowImage.vue";
import AtomLateralImage from "../atoms/AtomLateralImage.vue";
export default {
  name: "OrganismSidebar",
  components: { AtomLateralImage, AtomLateralFacebookFollowImage },
};
</script>

<style>
</style>