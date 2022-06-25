<template>
  <div class="HotelproVer">
    <div class="abouthotel">
      <div class="mbsoftlogo">
        <img src="../assets/hotel.png" alt="mbsoftlogo" />
        <img src="../assets/mbsoft2022-2.png" alt="mbsoftlogo" />
      </div>
      <div class="abouthoteldev">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae non
          et dignissimos minima excepturi laboriosam officiis repellendus eius
          quod voluptate, necessitatibus, optio consequuntur deleniti quaerat
          unde cumque. Consequatur, error magnam?
        </p>
      </div>
    </div>
    <div class="versions">
      <div class="version letestproduxt">
        <div class="vname">V1.0</div>
        <div class="name">Hotel Template</div>
        <div class="cost">Free</div>
        <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/github_PNG15.png" alt="github"
          /></a>
        </div>
        <div class="github">
          <a href="https://hotel.mbsoft-eg.com"
            ><img src="../assets/viewinmbsoft.png" alt="github"
          /></a>
        </div>
      </div>
      <div class="version">
        <div class="vname">V2.0</div>
        <div class="name">Hotel Template Pro</div>
        <div class="cost">15$</div>
        <!-- <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/github_PNG15.png" alt="github"
          /></a>
        </div> -->
        <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/envatomarket.png" alt="github"
          /></a>
        </div>
        <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/viewinmbsoft.png" alt="github"
          /></a>
        </div>
      </div>
      <div class="version soon">
        <div class="vname">V3.0</div>
        <div class="name">Hotel Template Pro 2</div>
        <div class="cost">SOON</div>
        <!-- <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/github_PNG15.png" alt="github"
          /></a>
        </div> -->
        <!-- <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/envatomarket.png" alt="github"
          /></a>
        </div> -->
        <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/viewinmbsoft.png" alt="github"
          /></a>
        </div>
      </div>
      <div class="version soon">
        <div class="vname">V4.0</div>
        <div class="name">Hotel Template Pro 2</div>
        <div class="cost">SOON</div>
        <!-- <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/github_PNG15.png" alt="github"
          /></a>
        </div> -->
        <!-- <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/envatomarket.png" alt="github"
          /></a>
        </div> -->
        <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/viewinmbsoft.png" alt="github"
          /></a>
        </div>
      </div>
      <div class="version soon">
        <div class="vname">V5.0</div>
        <div class="name">Hotel Template Pro 2</div>
        <div class="cost">SOON</div>
        <!-- <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/github_PNG15.png" alt="github"
          /></a>
        </div> -->
        <!-- <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/envatomarket.png" alt="github"
          /></a>
        </div> -->
        <div class="github">
          <a href="https://github.com/mostafabriek/hotel/releases/tag/v1.0"
            ><img src="../assets/viewinmbsoft.png" alt="github"
          /></a>
        </div>
      </div>
    </div>
    <div class="abouthotel">
      <p>
        All Right Reserved | Hotel Templates - By Mostafa Briek From MB SOFT inc
        © 2022
      </p>
    </div>
  </div>
</template>
<script>
export default {
  name: "HotelproVer",
  props: {},
};
</script>
<style scoped>
.HotelproVer {
  background: url(../assets/developFuncHms.png) no-repeat;
  width: 100%;
  background-attachment: fixed;
  background-size: cover;
}
.versions {
  display: flex;
  flex-direction: row;
  align-content: center;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  /* height: 300px; */
}
.version {
  width: 250px;
  color: #303030;
  background: #a5a5a570;
  height: 300px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin: 10px;
}
.vname {
  font-size: 40px;
}

.cost {
  color: green;
  font-size: 20px;
  margin: 20px;
}
.abouthotel {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 20px auto;
  padding: 20px 0;
  align-content: center;
}

.mbsoftlogo {
  margin: 5px 10px 5px 0;
}

.mbsoftlogo img {
  width: 60px;
}

.abouthoteldev {
  width: 35%;
  text-align: left;
  max-width: 500px;
  min-width: 200px;
}
@media screen and (max-width: 600px) {
  .abouthotel {
    display: flex;
    flex-direction: column;
  }
}
.version.letestproduxt {
  padding: 20px 10px;
  background: #f0f8ffd9;
  border: 1px solid #857d7d;
}
.version.soon {
  opacity: 0.5;
}
</style>
