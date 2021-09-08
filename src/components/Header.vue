<template>
  <header>
    <nav class="container">
      <img src="../assets/dc-logo.png" alt="" />
      <ul>
        <li v-for="element in elements" :key="element.id">
          <a href=""> {{ element.text }}</a>
        </li>
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
  padding-bottom: 20px;
}
li a {
  text-decoration: none;
  text-transform: uppercase;
  color: black;
  font-weight: 500;
  padding: 10px;
}
h1 a {
  text-decoration: none;
  font-family: "Roboto", sans-serif;
  color: white;
  font-weight: 100;
}
a:hover {
  border-bottom: 10px solid black;
  margin-top: 20px;
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
