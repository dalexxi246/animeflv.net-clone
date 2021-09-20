<template>
  <div>
    <div class="row">
      <span id="">ANIMES EN EMISIÓN</span>
      <img src="vector_play" alt="vector_play" srcset="vector_play" />
    </div>
    <ul>
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

<style>
</style>