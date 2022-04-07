/* eslint-disable */
<template>
  <main>
    <h2>Main</h2>
    <div class="container">
      <ComicCard
        v-for="(item, index) in series"
        :key="'comic-' + index"
        :title="item.series"
        :pathImg="item.thumb"
      />
    </div>
  </main>
</template>

/* eslint-disable */
<script>
import ComicCard from "@/components/Card.vue";

export default {
  name: "MainComponent",
  props: {
    comics: Array,
  },
  components: {
    ComicCard,
  },
};
</script>

/* eslint-disable */
<style lang="scss" scoped>
main {
  background-image: url("../assets/jumbotron.jpg");
  display: flex;
  align-items: flex-end;
  height: 100%;
  .container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
  }
}
</style>
