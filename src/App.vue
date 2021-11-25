<template>
  <div id="app">
    <Header/>
    <Jumbo/>
    <Main/>
    <Shop/>
    <Dc/>
    <Follow/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbo from "./components/Jumbo.vue";
import Main from "./components/Main.vue";
import Shop from "./components/Shop.vue";
import Dc from "./components/Dc.vue";
import Follow from "./components/Follow.vue";

export default {
  name: "App",
  components: {
    Header,
    Jumbo,
    Main,
    Shop, 
    Dc,
    Follow
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
