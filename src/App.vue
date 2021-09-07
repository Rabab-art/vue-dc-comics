<template>
  <div id="app">
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Main from "@/components/Main.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "App",
  components: {
    Header,
    Main,
    Footer,
  },
};
</script>

<style>
* {
  margin: auto;
  padding: 0;
  box-sizing: border-box;
  font-family: "Roboto", sans-serif;
}
.container {
  max-width: 1000px;
}
</style>
