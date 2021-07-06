<template>
  <div id="app">
    <Header/>
    <!-- <main>
      <Corpo/>
    </main>
    <Footer/> -->
  </div>
</template>

<script>

import Header from "./components/Header.vue";
// import Corpo from "./components/Corpo.vue";
// import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    
    Header,
    // Corpo,
    // Footer,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
