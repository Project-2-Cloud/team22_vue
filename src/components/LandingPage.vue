<template>
  <div class="LandingContainer">
    <img class="logo" src="../assets/logo2.png" alt="logo">
    <div class="LandingButtonsContainer">
      <button v-on:click="Lecturer()">Join us!</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingPage",
  props: {},
  methods: {
    Lecturer() {
      console.log("Lecturer");
    }
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.LandingContainer {
  background-color: #08379B;
  width: 100%;
  height: 90.5vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.LandingPageSmallText {
  margin-top: 3rem;
  width: 15rem;
}

.LandingButtonsContainer {
  margin-top: 8rem;
  display: flex;
  flex-direction: column;
}

.LandingButtonsContainer button {
  margin: 0rem 1rem;
  padding: 1rem 4rem;
  border: none;
}

.LandingButtonsContainer :first-child {
  background-color: rgb(180, 172, 255);
}

.LandingButtonsContainer :last-child {
  background-color: rgb(184, 255, 184);
}

.LandingButtonsContainer :hover {
  background-color: rgb(185, 185, 185);
}

.logo{
  width: 40vh;
}
</style>
