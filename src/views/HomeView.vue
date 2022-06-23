<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Recervition-template></Recervition-template>
    <rooms-template></rooms-template>
    <about-template></about-template>
    <Contact-View></Contact-View>
  </div>
</template>
<script>
// @ is an alias to /src
import RecervitionTemplate from "@/components/Recervition.vue";
import RoomsTemplate from "@/components/Rooms.vue";
import AboutTemplate from "@/views/AboutView.vue";
import ContactView from "@/views/contactVue.vue";

export default {
  name: "HomeView",
  components: {
    RecervitionTemplate,
    RoomsTemplate,
    AboutTemplate,
    ContactView,
  },
};
</script>
