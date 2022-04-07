/* eslint-disable */
<template>
  <header>
    <div class="container">
      <img src="../assets/dc-logo.png" alt="Logo DC" />
      <nav>
        <ul>
          <li>
            <a href="#">CHARACTERS</a>
          </li>
          <li>
            <a href="#">COMICS</a>
          </li>
          <li>
            <a href="#">MOVIES</a>
          </li>
          <li>
            <a href="#">TV</a>
          </li>
          <li>
            <a href="#">GAMES</a>
          </li>
          <li>
            <a href="#">COLLECTIBLES</a>
          </li>
          <li>
            <a href="#">VIDEOS</a>
          </li>
          <li>
            <a href="#">FANS</a>
          </li>
          <li>
            <a href="#">NEWS</a>
          </li>
          <li>
            <a href="#">SHOP</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

/* eslint-disable */
<script>
export default {
  name: "HeaderComponent",
};
</script>

/* eslint-disable */
<style lang="scss" scoped>
header {
  background-color: white;
}
.container {
  height: 80px;
  width: 80%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
img {
  height: 60px;
}
nav {
  height: 100%;
  display: flex;
  align-items: center;
  ul {
    display: flex;
    align-items: center;
  }
  li {
    margin: 0 8px;
    list-style-type: none;
  }
  a {
    text-decoration: none;
    color: black;
    font-weight: bold;
    font-size: 13px;
  }
}
</style>
