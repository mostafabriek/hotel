<template>
  <div class="recervation-temp">
    <div class="recervationbar">
      <div class="resback">
        <div class="reservation-form">
          <div class="hotelname">
            <span class="material-icons md-18">hotel</span>
            <p>Hotel Name</p>
          </div>
          <div>
            <label for="CheckIn">Check In</label>
            <input type="date" id="CheckIn" value="CheckIn" v-model="text" />
            <label for="CheckOut">Check Out</label>
            <input type="date" id="CheckOut" value="CheckOut" v-model="text" />
          </div>
          <div>
            <label for="Adults"
              ><span class="material-icons md-10">boy</span>Adults</label
            >
            <input
              type="number"
              id="Adults"
              value="Adults"
              v-model="text"
              placeholder="Adults"
            />
            <label for="Kids"
              ><span class="material-icons md-10">escalator_warning</span
              >Kids</label
            >
            <input
              type="number"
              id="Kids"
              value="Kids"
              v-model="text"
              placeholder="Kids"
            />
          </div>

          <input type="submit" value="Search availability" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "RecervitionTemplate",
  props: {},
};
</script>
<style>
.resback {
  background: url("../assets/marina.jpg") no-repeat;
  width: 90%;
  height: 735px;
  background-size: cover;
  margin: auto;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
label {
  color: white;
  padding: 7px;
}

input {
  margin: 20px 10px;
  padding: 5px 4px;
}
.reservation-form {
  display: flex;
  align-items: center;
  align-content: center;
  flex-wrap: wrap;
  flex-direction: row;
  padding: 0 45px 45px 45px;
  height: 180px;
  width: 570px;
  background: #6c6c6b69;
  margin: 25px;
}
input[type="submit"] {
  padding: 10px 60px;
  color: white;
  background: green;
  border: 0;
  border-radius: 8px;
  text-align: center;
  margin: auto;
  cursor: pointer;
}
.hotelname {
  background: white;
  padding: 20px 80px;
  font-size: 20px;
  font-weight: bold;
  border-left: 5px solid green;
  display: flex;
  flex-direction: row;
  align-items: center;
}
</style>
