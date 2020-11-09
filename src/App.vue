<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@font-face {
  font-family: "Montserrat";
  src: local("Montserrat"),
    url(./assets/Fonts/Montserrat-Regular.ttf) format("truetype");
}
:root,
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Montserrat;
  color: #2c3e50;
}
</style>
