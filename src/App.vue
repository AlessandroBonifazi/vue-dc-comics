<template>
  <div class="body">
    <div id="app">
      <Header />
      <Main :comics="series" />
      <Footer />
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Footer from "./components/Footer.vue";
// data
import series from "@/assets/dc-comics";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
  data() {
    return {
      series,
    };
  },
};
</script>

<style lang="scss">
// @import "@/variables";

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.body {
  background-color: black;
  height: 100vh;
  display: flex;
  flex-direction: column;
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin: auto 0;
    height: 95vh;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    background-color: aliceblue;
  }
}
</style>
