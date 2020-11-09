<template>
  <div id="app">
    <Navbar></Navbar>
    <router-view />
  </div>
</template>
<script>
import Navbar from "@/components/Navbar.vue";

export default {
  name: "App",
  components: {
    Navbar
  }
};
</script>
<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");

// @font-face {
//   font-family: "Montserrat";
//   src: local("Montserrat"),
//     url(./assets/Fonts/Montserrat-Regular.ttf) format("truetype");
// }
:root,
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Montserrat", sans-serif;
  font-size: 16px;
}
#app {
  background: #f2fbfb;
  min-height: 100vh;
}
@media only screen and (max-width: 768px) {
  :root,
  body {
    font-size: 10px;
  }
}
</style>
