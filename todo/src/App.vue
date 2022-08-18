<template>
  <div id="app">
    <home />
  </div>
</template>
<script>
import home from "./components/Home.vue";
export default {
  name: "App",
  components: {
    home,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}
html,
body {
  width: 100%;
  height: 100%;
}
#app {
    background: url("../resources/mainBack.png");
  background-size: cover;
  font-family: "Ubuntu", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 100%;
  height: 100%;
}
</style>
