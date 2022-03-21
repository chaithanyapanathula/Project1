<template>
  <div id="app">
    <h1>Power Oil & Lubricants</h1>
    <HomePageDetails />
    <br>
    <SliderShow/>
    
  </div>
</template>

<script>
import HomePageDetails from "./components/HomePage.vue";
import SliderShow from "./components/SliderShow.vue"

export default {
  name: "App",
  components: {
    HomePageDetails,
    SliderShow,
    
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
