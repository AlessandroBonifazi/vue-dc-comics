/* eslint-disable */
<template>
  <div class="card">
    <img :src="pathImg" />
    <h3>{{ title }}</h3>
  </div>
</template>

/* eslint-disable */
<script>
export default {
  name: "ComicCard",
  props: {
    pathImg: String,
    title: String,
  },
};
</script>

/* eslint-disable */
<style lang="scss" scoped>
.card {
  text-align: center;
  width: calc(100% / 6);
  color: white;
  padding: 1rem;
  h3 {
    font-size: 15px;
  }
  img {
    height: 120px;
  }
}
</style>