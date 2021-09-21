<template>
  <div>
    <div class="my-2">
      <span class="col-10 text-start">ANIMES EN EMISIÓN</span>
      <b-icon class="col-2" icon="play-fill" />
    </div>
    <ul class="list-unstyled">
      <li v-for="show in shows" :key="show.id">
        <atom-show-broadcasting-now :name="show.name" :showType="show.type" />
      </li>
    </ul>
  </div>
</template>

<script>
import AtomShowBroadcastingNow from "../atoms/AtomShowBroadcastingNow.vue";
export default {
  components: { AtomShowBroadcastingNow },
  data() {
    return {
      shows: [
        {
          id: 0,
          name: "One Piece",
          type: "Anime",
        },
        {
          id: 1,
          name: "Sailor Moon",
          type: "Anime",
        },
        {
          id: 2,
          name: "Dragon Ball Z",
          type: "Anime",
        },
      ],
    };
  },
};
</script>

<style scoped>
</style>