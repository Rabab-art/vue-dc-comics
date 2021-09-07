<template>
  <footer>
    <div class="row container">
      <div class="col">
        <a href="" alt="" class="sing-up"><h2>SING UP NOW</h2> </a>
      </div>
      <div class="col social">
        <p>FOLLOW US</p>
        <img src="../assets/footer-facebook.png" alt="" />
        <img src="../assets/footer-periscope.png" alt="" />
        <img src="../assets/footer-pinterest.png" alt="" />
        <img src="../assets/footer-twitter.png" alt="" />
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: "Footer",
};
</script>

<style scope>
footer {
  height: 80px;
  background-color: rgb(64, 73, 73);
}

.sing-up {
  font-weight: 600;
  color: white;
  vertical-align: 80px;
  text-decoration: none;
  border: 4px solid dodgerblue;
  padding: 5px;
}
footer .col {
  display: flex;
  height: 100%;
}

.sing-up:hover {
  border: 4px solid transparent;
}
.social p {
  text-decoration: uppercase;
  color: dodgerblue;
  font-weight: 600;
}
</style>