<template>
  <div class="home">
    <div id="home-body">
      <div id="text-on-home">
        <p id="main-title">Connect with your nearest sports community</p>
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

export default {
  name: "Home"
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
  font-weight: bolder;
  color: #000;
}
</style>
