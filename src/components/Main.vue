<template>
  <main>
    <div class="row container">
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
      <div class="container row">
        <div class="col-6">
          <h2>DC COMICS</h2>
          <ul>
            <li>parole</li>
            <li>parole</li>
            <li>parole</li>
            <li>parole</li>
            <li>parole</li>
            <li>parole</li>
            <li>parole</li>
          </ul>

          <h2>SHOP</h2>
          <ul>
            <li></li>
            <li></li>
          </ul>

          <h2>DC</h2>
          <ul>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
          </ul>
        </div>
        <div class="col-6 logo-footer">
          <img src="../assets/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </section>
  </main>
</template>
<script>
export default {
  name: "Main",
};
</script>

<style scope>
main {
  background-color: dodgerblue;
  height: 120px;
}

.row {
  display: flex;
  flex-basis: 1;
}
.col {
  padding: 5px;
  display: flex;
  align-items: center;
  height: 100px;
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
  height: 110%;
  width: 350px;
}
h2 {
  color: white;
}
section .row {
  height: 100%;
}
</style>