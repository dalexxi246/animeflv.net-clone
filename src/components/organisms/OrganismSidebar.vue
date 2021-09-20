<template>
  <div>
    <atom-lateral-image />
    <atom-lateral-facebook-follow-image />
    <molecule-series-broadcasting-now/>
  </div>
</template>

<script>
import AtomLateralFacebookFollowImage from "../atoms/AtomLateralFacebookFollowImage.vue";
import AtomLateralImage from "../atoms/AtomLateralImage.vue";
import MoleculeSeriesBroadcastingNow from '../molecules/MoleculeSeriesBroadcastingNowHeader.vue';
export default {
  name: "OrganismSidebar",
  components: { AtomLateralImage, AtomLateralFacebookFollowImage, MoleculeSeriesBroadcastingNow },
};
</script>

<style>
</style>