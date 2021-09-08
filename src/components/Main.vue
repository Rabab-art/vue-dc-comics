<template>
  <main>
    <div class="row container icons">
      <div class="col">
        <img src="../assets/buy-comics-digital-comics.png" alt="" /><span
          >DIGITAL COMICS</span
        >
      </div>
      <div class="col">
        <img src="../assets/buy-comics-merchandise.png" alt="" /><span
          >DC MERCHANDISE</span
        >
      </div>
      <div class="col">
        <img src="../assets/buy-comics-subscriptions.png" alt="" /><span
          >SUBSCRIPTION</span
        >
      </div>
      <div class="col">
        <img src="../assets/buy-comics-shop-locator.png" alt="" /><span
          >COMIC SHOP LOCATOR
        </span>
      </div>
      <div class="col">
        <img src="../assets/buy-dc-power-visa.svg" alt="" /><span>
          DC POWER VISA</span
        >
      </div>
    </div>
    <section>
      <div class="container row menu">
        <div class="col list">
          <h2>DC COMICS</h2>
          <ul>
            <li v-for="element in elements" :key="element.id">
              {{ elemt.text }}
            </li>
          </ul>
          <br />
          <h2>SHOP</h2>
          <ul>
            <li>Shop DC</li>
            <li>Shop DC Collection</li>
          </ul>
        </div>

        <div class="col list">
          <h2>DC</h2>
          <ul>
            <li>Terms of Use</li>
            <li>Privacy</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>
        <div class="col list">
          <h2>Sites</h2>
          <ul>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
        <div class="col logo-footer">
          <img src="" alt="" />
        </div>
      </div>
    </section>
  </main>
</template>
<script>
export default {
  name: "Main",
  data() {
    return {
      elements: [
        {
          text: "Characters",
          url: "",
          current: false,
        },
        {
          text: "Comics",
          url: "#",
          current: true,
        },
        {
          text: "Movies",
          url: "#",
          current: false,
        },
        {
          text: "TV",
          url: "#",
          current: false,
        },
        {
          text: "Games",
          url: "#",
          current: false,
        },
        {
          text: "Collectibles",
          url: "#",
          current: false,
        },
        {
          text: "Videos",
          url: "#",
          current: false,
        },
        {
          text: "Fans",
          url: "#",
          current: false,
        },
        {
          text: "News",
          url: "#",
          current: false,
        },
        {
          text: "Shop",
          url: "#",
          current: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
main {
  background-color: dodgerblue;
}
.icons {
  background-color: dodgerblue;
  height: 120px;
}

.row {
  display: flex;
  flex-basis: 1;
}
.icons .col {
  padding: 5px;
  display: flex;
  align-items: center;
  height: 70px;
}
.col img {
  height: 100%;
}
span {
  color: white;
  align-items: center;
  padding: 5px;
  font-size: 15px;
}
section {
  background-image: url(../assets/footer-bg.jpg);
  background-size: cover;
  height: 300px;
}
.col.logo-footer {
  height: 100%;
  width: 350px;
  background-image: url(../assets/dc-logo-bg.png);
  background-size: cover;
}
h2 {
  color: white;
  margin-bottom: 5px;
}
section .row {
  height: 100%;
}
section li {
  display: flex;
  flex-wrap: wrap;
  padding: 0;
  height: 100%;
}
.list {
  margin-top: 20px;
  margin-left: 10px;
  margin-right: 20px;
  color: white;
  line-height: 2 em;
}

.list li {
  color: grey;
  font-weight: 100;
  font-size: 12px;
}
</style>