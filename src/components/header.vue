<template>
  <div class="HeaderView">
    <header>
      <p>
        all right reserved | Hotel Templates v1.0 - By
        <a href="//mostafabriek.com"> Mostafa Briek </a> From
        <a href="//mbsoft-eg.com"> MB SOFT inc</a>
        © 2022
      </p>
    </header>
  </div>
</template>
<script>
export default {
  name: "HeaderView",
  props: {},
};
</script>
<style>
.HeaderView {
  width: 100%;
  padding: 20px 0;
  background: linear-gradient(
    135deg,
    rgb(24, 25, 34) 2%,
    rgb(11, 12, 19) 58%,
    rgb(36, 63, 113) 100%
  );
  color: white;
  margin: 0 0 0 0;
}
@media screen and (max-width: 600px) {
  .rooms {
    flex-direction: column !important;
    margin: 20px auto !important;
  }

  .room {
    margin: 10px auto !important;
  }
  .reservation-form {
    display: flex;
    justify-content: center !important;
    align-items: center;
    flex-wrap: wrap !important;
    align-content: center !important;
    flex-direction: row !important;
    width: 100px !important;
    margin: 30px !important;
    height: 463px !important;
    padding: 15px 75px 35px !important;
  }

  .resback {
    display: flex !important;
    justify-content: center !important;
  }
}
</style>
