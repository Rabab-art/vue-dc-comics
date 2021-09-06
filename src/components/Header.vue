<template>
  <header>
    <nav class="container">
      <img src="../assets/dc-logo.png" alt="" />
      <ul>
        <li><a href="">Characters</a></li>
        <li><a href="">Comes </a></li>
        <li><a href="">Movies </a></li>
        <li><a href="">TV </a></li>
        <li><a href="">Games </a></li>
        <li><a href="">Video </a></li>
        <li><a href="">Fans </a></li>
        <li><a href="">News </a></li>
        <li><a href="">Shp </a></li>
      </ul>
    </nav>
    <div class="barra"><h1 class="container">Contente Goes here</h1></div>
  </header>
</template>
<script>
export default {
  name: "Header",
};
</script>

<style >
nav {
  display: flex;
  justify-content: space-between;
}
ul {
  display: inline;
  justify-content: flex-end;
}
li {
  display: inline-block;
  padding: 5px;
}

.barra {
  height: 100px;
  background-color: black;
}
.barra h1 {
  color: white;
  line-height: 100px;
}
</style>
