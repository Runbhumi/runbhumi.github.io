<template>
  <div id="nav">
    <!-- <router-link to="/">Home</router-link> -->
    <h1 id="icon-and-logo">
      <img
        src="../assets/icon.png"
        alt="Runbhumi"
        height="48px"
        style="padding:0 0 0 8px; border-radius:12px;"
      />
      <router-link to="/" id="name">Runbhumi</router-link>
    </h1>
    <h2><router-link to="/feedback">Feedback</router-link></h2>
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
  padding: 24px 150px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  #icon-and-logo {
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: 800;
    font-style: italic;
  }
  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;

    &.router-link-exact-active {
      color: #2dadc2;
    }
  }
}
</style>
