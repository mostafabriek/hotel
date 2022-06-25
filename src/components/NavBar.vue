<template>
  <div class="navbar">
    <div class="navbarp">
      <nav>
        <router-link to="/" class="logodiv">
          <img class="logo" alt="Vue logo" src="../assets/logo.png" />
          <p>Hotel</p>
        </router-link>
        <router-link to="/rooms">Rooms</router-link>
        <router-link to="/about">About</router-link>
        <router-link to="/contact">Contact</router-link>
      </nav>
      <div class="github">
        <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
          ><img src="../assets/github_PNG15.png" alt="github"
        /></a>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "NavBar",
  props: {},
};
</script>
<style>
.navbar .github img {
  width: 80px;
}
.github img {
  width: 100px;
}
.navbarp {
  display: flex;
  justify-content: space-evenly;
  align-content: center;
  align-items: center;
  width: 90%;
  margin: auto;
}
.logodiv {
  display: flex;
  align-content: center;
  flex-direction: row;
  align-items: center;
  flex-wrap: nowrap;
  justify-content: center;
}
.logo {
  width: 60px;
  height: auto;
}
* {
  padding: 0;
  margin: 0;
}
.navbar {
  width: 100%;
  height: 70px;
  background: white;
}
nav a {
  margin: 10px;
  text-decoration: none;
}

nav {
  /* display: flex;
  align-content: center;
  flex-direction: row;
  align-items: center;
  flex-wrap: nowrap;
  justify-content: center; */
  display: flex;
  width: 100%;
  align-content: center;
  flex-direction: row;
  align-items: center;
  flex-wrap: nowrap;
  justify-content: flex-start;
  margin: auto;
}
</style>
