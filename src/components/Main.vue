/* eslint-disable */
<template>
  <main>
    <div class="frame">
      <div class="container">
        <ComicCard
          v-for="(item, index) in comics"
          :key="'comic-' + index"
          :title="item.series"
          :pathImg="item.thumb"
        />
      </div>
      <button>LOAD MORE</button>
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
  background-position: center top;
  display: flex;
  align-items: flex-end;
  .frame {
    width: 100%;
    margin-top: 400px;
    background-color: #1c1c1c;
    .container {
      max-width: 1200px;
      margin: 0 auto;
      display: flex;
      flex-wrap: wrap;
    }
    button {
      color: white;
      padding: 10px 50px;
      background-color: #097df6;
      margin: 30px 0px;
      border: 1px solid transparent;
    }
  }
}
</style>
