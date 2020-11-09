<template>
  <div class="home">
    <Navbar></Navbar>
    <div id="home-body">
      <div id="text-on-home">
        <h1 id="main-title">Connect with your nearest sports community</h1>
        <h3>
          we provide you with a platform to connect with people of same sports
          interests and play with them outdoors
        </h3>
      </div>
      <img src="../assets/sports-illustration.svg" alt="" width="50%" />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Home",
  components: {
    Navbar
  }
};
</script>

<style lang="scss" scoped>
#home-body {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 8rem;
}
#main-title {
  font-family: Montserrat;
  font-size: 54px;
  font-weight: 700;
  font-style: italic;
  color: #000;
}
</style>
