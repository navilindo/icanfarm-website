<template>
  <div>
    <Footer />
  </div>
</template>

<script>

import MyFooter from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Footer: MyFooter,
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
