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
        <li><a href="">Shop </a></li>
      </ul>
    </nav>
    <div class="insertion">
      <h1 class="container"><a href="">--> Contente goes here </a></h1>
    </div>
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
  height: 100px;
}

img {
  height: 100%;
  padding: 20px;
}
ul {
  display: inline;
  justify-content: flex-end;
}
li {
  display: inline-block;
  padding: 5px;
}
li a {
  text-decoration: none;
  text-transform: uppercase;
  color: black;

  font-weight: 500;
}
h1 a {
  text-decoration: none;
  font-family: "Roboto", sans-serif;
  color: white;
  font-weight: 100;
}
a:hover {
  border-bottom: 10px solid black;
}

.insertion {
  height: 80px;
  background-color: black;
}
.insertion h1 {
  color: white;
  line-height: 80px;
}
</style>
