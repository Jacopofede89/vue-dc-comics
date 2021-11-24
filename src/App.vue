<template>
  <div id="app">
    <Header/>
    <Main/>
    <Shop/>
    <Dc/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import Shop from "./components/Shop.vue";
import Dc from "./components/Dc.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    Shop, 
    Dc
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
}
*{
  margin:0;
}
</style>
