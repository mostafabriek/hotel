<template>
  <div class="rooms-temp">
    <div class="rooms">
      <div class="room">
        <div class="roomimg">
          <img src="../assets/room_single.jpg" alt="" />
        </div>
        <div class="roomname">Single Room</div>
        <div class="roompricefroom">Start From 29 $</div>
        <div class="infoicons">
          <span class="material-icons md-18">ac_unit</span
          ><span class="material-icons md-18">smart_display</span
          ><span class="material-icons md-18">light</span>
          <span class="material-icons md-18">wc</span>
          <span class="material-icons md-18">shower</span>
        </div>
        <div class="showrooms">choose room</div>
      </div>
      <div class="room">
        <div class="roomimg">
          <img src="../assets/doubleroom.jpg" alt="" />
        </div>
        <div class="roomname">Double Room</div>
        <div class="roompricefroom">Start From 50 $</div>
        <div class="infoicons">
          <span class="material-icons md-18">ac_unit</span
          ><span class="material-icons md-18">accessible_forward</span
          ><span class="material-icons md-18">chair</span
          ><span class="material-icons md-18">deck</span
          ><span class="material-icons md-18">light</span>
          <span class="material-icons md-18">wc</span>
          <span class="material-icons md-18">shower</span>
          <span class="material-icons md-18">room_service</span>
        </div>
        <div class="showrooms">choose room</div>
      </div>
      <div class="room">
        <div class="roomimg">
          <img src="../assets/trouble.jpg" alt="" />
        </div>
        <div class="roomname">Trouble Room</div>
        <div class="roompricefroom">Start From 80 $</div>
        <div class="infoicons">
          <span class="material-icons md-18">ac_unit</span
          ><span class="material-icons md-18">accessible_forward</span
          ><span class="material-icons md-18">chair</span
          ><span class="material-icons md-18">smart_display</span
          ><span class="material-icons md-18">deck</span
          ><span class="material-icons md-18">airplay</span
          ><span class="material-icons md-18">light</span>
          <span class="material-icons md-18">wc</span>
          <span class="material-icons md-18">shower</span>
          <span class="material-icons md-18">king_bed</span>
        </div>
        <div class="showrooms">choose room</div>
      </div>
      <div class="room">
        <div class="roomimg">
          <img src="../assets/room_deluxe.jpg" alt="" />
        </div>
        <div class="roomname">Dulax Room</div>
        <div class="roompricefroom">Start From 129 $</div>
        <div class="infoicons">
          <span class="material-icons md-18">ac_unit</span
          ><span class="material-icons md-18">accessible_forward</span
          ><span class="material-icons md-18">chair</span
          ><span class="material-icons md-18">smart_display</span
          ><span class="material-icons md-18">deck</span
          ><span class="material-icons md-18">airplay</span
          ><span class="material-icons md-18">light</span>
          <span class="material-icons md-18">wc</span>
          <span class="material-icons md-18">shower</span>
          <span class="material-icons md-18">room_service</span>
          <span class="material-icons md-18">king_bed</span>
          <span class="material-icons md-18">meeting_room</span>
        </div>
        <div class="showrooms">choose room</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "RoomsTemplate",
  props: {},
};
</script>
<style>
.roomimg img {
  width: 300px;
  height: auto;
}

.room {
  width: 300px;
  height: 410px;
  /* background: #919ec8cc; */
  color: #675d44;
  position: relative;
}

.rooms {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-evenly;
  width: 90%;
  margin: 50px auto;
}

.roomimg {
  height: 200px;
  overflow: hidden;
}
.infoicons {
  display: flex;
  margin: 20px auto;
  width: 80%;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
}
.roomname {
  font-size: 26px;
  margin: 20px;
}

.roompricefroom {
  font-size: 14px;
}

.showrooms {
  background: #9ca0c6;
  /* border: 1px solid gray; */
  bottom: 0px;
  position: absolute;
  width: 100%;
  font-size: 20px;
  border-radius: 25px;
  color: white;
  padding: 5px;
  font-size: 15px;
  cursor: pointer;
}
</style>
