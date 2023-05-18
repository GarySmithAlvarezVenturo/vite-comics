<script></script>

<template>
  <footer>
    <section class="footer-buy">
      <div class="options">
        <div>
          <img
            src="../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png"
            alt=""
          />
          <p>DIGITAL COMICS</p>
        </div>
        <div>
          <img
            src="../assets/vue-dc-comics-1/img/buy-comics-merchandise.png"
            alt=""
          />
          <p>DC MERCHANDISE</p>
        </div>
        <div>
          <img
            src="../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png"
            alt=""
          />
          <p>SUBSCRIPTION</p>
        </div>
        <div>
          <img
            src="../assets/vue-dc-comics-1/img/buy-comics-shop-locator.png"
            alt=""
          />
          <p>COMIC SHOP LOCATOR</p>
        </div>
        <div>
          <img
            src="../assets/vue-dc-comics-1/img/buy-dc-power-visa.svg"
            alt=""
          />
          <p>DC POWER VISA</p>
        </div>
      </div>
    </section>

    <div class="footer-img">
      <div class="contacts">
        <div>
          <div class="column">
            <ul>
              <li class="title">DC COMICS</li>
              <li><a href="">Characters</a></li>
              <li><a href="">Comics</a></li>
              <li><a href="">Movies</a></li>
              <li><a href="">TV</a></li>
              <li><a href="">Games</a></li>
              <li><a href="">Videos</a></li>
              <li><a href="">News</a></li>
            </ul>

            <ul>
              <li class="title">SHOP</li>
              <li><a href="">Shop DC</a></li>
              <li><a href="">Shop DC Collectibles</a></li>
            </ul>
          </div>

          <div>
            <ul>
              <li class="title">DC</li>
              <li><a href="">Terms Of use</a></li>
              <li><a href="">Privacy policy(New)</a></li>
              <li><a href="">Ad Choices</a></li>
              <li><a href="">Advertising</a></li>
              <li><a href="">Jobs</a></li>
              <li><a href="">Subscriptions</a></li>
              <li><a href="">Talent Workshops</a></li>
              <li><a href="">CPSC Certificates</a></li>
              <li><a href="">Ratings</a></li>
              <li><a href="">Shop Help</a></li>
              <li><a href="">Contatc Us</a></li>
            </ul>
          </div>

          <div>
            <ul>
              <li class="title">SITES</li>
              <li><a href="">DC</a></li>
              <li><a href="">Mad Megazine</a></li>
              <li><a href="">DC Kids</a></li>
              <li><a href="">DC Universe</a></li>
              <li><a href="">DC Power Visa</a></li>
            </ul>
          </div>
        </div>

        <div>
          <img src="../assets/vue-dc-comics-1/img/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </div>

    <div class="footer-end">
      <section class="socials">
        <button>SIGN-UP NOW!</button>

        <div>
          <h3>FOLLOW US</h3>
          <img src="../assets/vue-dc-comics-1/img/footer-facebook.png" alt="" />
          <img src="../assets/vue-dc-comics-1/img/footer-twitter.png" alt="" />
          <img src="../assets/vue-dc-comics-1/img/footer-youtube.png" alt="" />
          <img
            src="../assets/vue-dc-comics-1/img/footer-pinterest.png"
            alt=""
          />
          <img
            src="../assets/vue-dc-comics-1/img/footer-periscope.png"
            alt=""
          />
        </div>
      </section>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
@use "./../assets/styles/partials/variables.scss" as *;

.footer-buy {
  background-color: rgb(2, 130, 249);
}

.options {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 10rem;
  max-width: 1200px;
  margin: auto;

  div {
    display: flex;
    align-items: center;
    padding-inline: 2rem;

    img {
      width: 40px;
    }

    p {
      color: white;
      white-space: nowrap;
    }
  }
}

.footer-img {
  background-image: url(../assets/vue-dc-comics-1/img/footer-bg.jpg);
  background-size: cover;
  overflow: hidden;
}

.contacts {
  max-width: 1200px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 23rem;

  div {
    display: flex;
    gap: 1.5rem;

    .column {
      display: flex;
      flex-direction: column;
    }
  }

  .title {
    color: white;
    margin-bottom: 0.5rem;
    margin-top: 0.5rem;
  }

  li {
    list-style: none;

    a {
      text-decoration: none;
      color: rgb(120, 124, 132);
      font-size: 0.7rem;
    }
  }
}

.footer-end {
  background-color: rgb(48, 48, 48);
  height: 12rem;
}

.socials {
  max-width: 1200px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 10rem;

  button {
    background-color: transparent;
    color: white;
    border: 2px solid rgb(12, 119, 234);
    padding: 0.7rem;
    font-size: 1rem;
  }

  div {
    display: flex;
    align-items: center;
    gap: 1rem;

    h3 {
      color: rgb(12, 119, 234);
    }
  }
}
</style>
