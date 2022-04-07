/* eslint-disable */
<template>
  <footer>
    <!-- link -->
    <section class="bg-primary h-100">
      <div class="container">
        <div class="card-container">
          <div class="card">
            <img src="../assets/buy-comics-digital-comics.png" alt="" />
            <a href="#">DIGITAL COMICS</a>
          </div>
          <div class="card">
            <img src="../assets/buy-comics-merchandise.png" alt="" />
            <a href="#">DC MERCHANDISE</a>
          </div>
          <div class="card">
            <img src="../assets/buy-comics-subscriptions.png" alt="" />
            <a href="#">SUBSCRIPTIONS</a>
          </div>
          <div class="card">
            <img src="../assets/buy-comics-shop-locator.png" alt="" />
            <a href="#">COMIC SHOP LOCATOR</a>
          </div>
          <div class="card">
            <img src="../assets/buy-dc-power-visa.svg" alt="" />
            <a href="#">DC POWER VISA</a>
          </div>
        </div>
      </div>
    </section>
    <!-- info -->
    <section>
      <div class="container-links">
        <div class="info">
          <div class="link">
            <ul>
              <h3>DC COMICS</h3>
              <li>
                <a href="#">Characters</a>
              </li>
              <li>
                <a href="#">Comics</a>
              </li>
              <li>
                <a href="#">Movies</a>
              </li>
              <li>
                <a href="#">TV</a>
              </li>
              <li>
                <a href="#">Games</a>
              </li>
              <li>
                <a href="#">Videos</a>
              </li>
              <li>
                <a href="#">News</a>
              </li>
            </ul>

            <ul>
              <h3>SHOP</h3>
              <li>
                <a href="#">Shop DC</a>
              </li>
              <li>
                <a href="#">Shop DC Collectibles</a>
              </li>
            </ul>
          </div>

          <div class="link">
            <ul>
              <h3>DC</h3>
              <li>
                <a href="#">Terms of use</a>
              </li>
              <li>
                <a href="#">Privacy Policy(New)</a>
              </li>
              <li>
                <a href="#">AD Choices</a>
              </li>
              <li>
                <a href="#">Advertising</a>
              </li>
              <li>
                <a href="#">Jobs</a>
              </li>
              <li>
                <a href="#">Subscriptions</a>
              </li>
              <li>
                <a href="#">Talent Workshops</a>
              </li>
              <li>
                <a href="#">CPSC Certificates</a>
              </li>
              <li>
                <a href="#">Ratings</a>
              </li>
              <li>
                <a href="#">Shop Help</a>
              </li>
              <li>
                <a href="#">Contact Us</a>
              </li>
            </ul>
          </div>

          <div class="link">
            <ul>
              <h3>Sites</h3>
              <li>
                <a href="#">DC</a>
              </li>
              <li>
                <a href="#">Mad Magazine</a>
              </li>
              <li>
                <a href="#">DC Kids</a>
              </li>
              <li>
                <a href="#">DC Universe</a>
              </li>
              <li>
                <a href="#">DC Power Visa</a>
              </li>
            </ul>
          </div>
        </div>
        <div class="bg-logo"></div>
      </div>
    </section>
    <!-- social -->
    <section class="bg-grey h-80">
      <div class="container-social">
        <div class="signup">
          <button>SIGN UP NOW!</button>
        </div>

        <div class="social">
          <h3>FOLLOW US</h3>
          <img src="../assets/footer-facebook.png" alt="faceBook" />
          <img src="../assets/footer-twitter.png" alt="twitter" />
          <img src="../assets/footer-youtube.png" alt="youtube" />
          <img src="../assets/footer-pinterest.png" alt="pinterest" />
          <img src="../assets/footer-periscope.png" alt="periscope" />
        </div>
      </div>
    </section>
  </footer>
</template>

/* eslint-disable */
<script>
export default {
  name: "FooterComponent",
};
</script>

/* eslint-disable */
<style lang="scss" scoped>
// Utilities
.bg-primary {
  background-color: #0282f9;
}
.bg-grey {
  background-color: #303030;
}
.h-80 {
  height: 80px;
}
.h-60 {
  height: 60px;
}
.h-100 {
  height: 100px;
}
.h-130 {
  height: 130px;
}
// Content
footer {
  background-image: url(../assets/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: top;
}
.bg-logo {
  background-image: url(../assets/dc-logo-bg.png);
  background-position: center;
  background-repeat: no-repeat;
  width: 50%;
}
.container {
  height: 100%;
  width: 80%;
  margin: 0 auto;
}
.container-links {
  height: 100%;
  width: 80%;
  margin: 0px auto;
  display: flex;
  justify-content: space-between;
}
.container-social {
  height: 100%;
  width: 80%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.card-container {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.card {
  width: 20%;
  display: flex;
  align-items: center;
  img {
    height: 50px;
  }
}
a {
  text-decoration: none;
  font-weight: bold;
  font-size: 13px;
  color: white;
  margin-left: 10px;
}

.info {
  display: flex;
  column-gap: 30px;
}
.link {
  text-align: left;
  padding: 35px 20px;
  ul {
    margin-bottom: 10px;
  }
  li {
    list-style-type: none;
  }
  a {
    color: grey;
    text-decoration: none;
    font-size: 14px;
  }
  h3 {
    color: white;
    margin-bottom: 10px;
  }
}
.social {
  display: flex;
  align-items: center;
  column-gap: 20px;
  h3 {
    color: #0282f9;
  }
  img {
    height: 25px;
  }
}
button {
  background-color: transparent;
  padding: 15px 10px;
  border: 2px solid #0282f9;
  color: white;
  font-size: 16px;
}
</style>
