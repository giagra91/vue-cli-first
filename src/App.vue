<template>
  <div id="app">
    <TitleVue></TitleVue>
    <HeroJumbo />
  </div>
</template>

<script>
import TitleVue from "./components/NewTitle.vue";
import HeroJumbo from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    TitleVue,
    HeroJumbo,
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
