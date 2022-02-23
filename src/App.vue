<template>
  <!-- <nav>
    <router-link to="/">Home</router-link>
  </nav>
  <router-view/> -->
  <Home />
</template>

<script>
import Home from "@/views/HomeView.vue";

export default {
  name: "app",
  components: {
    Home,
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
}

</style>
