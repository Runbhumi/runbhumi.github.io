<template>
  <div class="home">
    <div id="home-body" style="min-height:90vh;">
      <div id="text-on-home">
        <p id="main-title">Connect with your nearest sports community</p>
        <h3>
          Enter the sporting world to make your dream team and compete with
          others in your locality. Connect | Schedule | Play
        </h3>
      </div>
      <img src="../assets/sports-illustration.svg" alt="" width="45%" />
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
  font-size: 3.5rem;
  font-weight: bolder;
  color: #000;
}
@media only screen and (max-width: 768px) {
  #home-body {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 0 4rem;
    text-align: center;
  }
}
</style>
