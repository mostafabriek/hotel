<template>
  <div id="app">
    <link
      href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet"
    />
    <nav-bar></nav-bar>
    <div id="con">
      <router-view />
    </div>
    <header-view></header-view>
  </div>
</template>
<script>
import NavBar from "@/components/NavBar.vue";
import HeaderView from "@/components/header.vue";

export default {
  name: "HomeView",
  components: {
    NavBar,
    HeaderView,
  },
};
</script>
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
span {
  padding: 0 2px;
}
nav {
  padding: 0px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
#con {
  min-height: 80vh;
}
a {
  text-decoration: none;
  color: #e7e7e7;
}
@media screen and (max-width: 600px) {
  .rooms {
    flex-direction: column !important;
    margin: 20px auto;
  }

  .room {
    margin: 10px auto !important;
  }
  .reservation-form {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    align-content: center;
    flex-direction: row;
    width: 100px;
    margin: 30px;
    height: 463px;
    padding: 15px 75px 35px;
  }

  .resback {
    display: flex;
    justify-content: center;
  }
}
</style>
