<template>
  <div id="nav">
    <!-- <router-link to="/">Home</router-link> -->
    <h1 id="icon-and-logo">
      <img src="../assets/icon.png" alt="Runbhumi" height="32px" />
      <router-link to="/">Runbhumi</router-link>
    </h1>
    <router-link to="/about">Contact us</router-link>
  </div>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#nav {
  padding: 1rem 8rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  #icon-and-logo {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;

    &.router-link-exact-active {
      color: #00adb5;
    }
  }
}
</style>
