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
          >DIGITAL COMICS</span
        >
      </div>
      <div class="col">
        <img src="../assets/buy-comics-shop-locator.png" alt="" /><span
          >DIGITAL COMICS</span
        >
      </div>
      <div class="col">
        <img src="../assets/buy-comics-subscriptions.png" alt="" /><span
          >DIGITAL COMICS</span
        >
      </div>
      <div class="col">
        <img src="../assets/buy-dc-power-visa.svg" alt="" /><span
          >DIGITAL COMICS</span
        >
      </div>
    </div>
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
  height: 150px;
}

.row {
  display: flex;
  flex-basis: 1;
}
.col {
  padding: 5px;
  display: flex;
  align-items: center;
}
img {
  max-width: auto;
}
span {
  color: white;
  align-items: center;
  padding: 5px;
  font-size: 15px;
}
</style>