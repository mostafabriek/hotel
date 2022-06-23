<template>
  <div class="ContactVue">
    <div class="contactbanar">
      <div class="concom">
        <h1>contact</h1>
        <p>If you have any questions, do not hesitate to ask them.</p>
        <span class="material-icons md-18">map</span> Chicago, US <br />
        <span class="material-icons md-18">phone</span> 01111111111 <br />
        <span class="material-icons md-18">email</span> Email: mail@mail.com
      </div>
    </div>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d58654.53757669386!2d-51.280828151093075!3d-23.246412897022694!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94eb5b4a2872c61f%3A0xf02ebb4db2f3b7d!2sHotel%20Thomasi!5e0!3m2!1sen!2seg!4v1655947795478!5m2!1sen!2seg"
      width="100%"
      height="450"
      style="border: 0"
      allowfullscreen=""
      loading="lazy"
      referrerpolicy="no-referrer-when-downgrade"
    ></iframe>
  </div>
</template>
<script></script>
<style>
.ContactVue {
  width: 90%;
  margin: 50px auto;
}
.ContactVue span {
  font-size: 15px !important;
}
.concom {
  top: 380px;
  position: relative;
  color: #e8e7ec;
}

.contactbanar {
  position: relative;
  /* width: 90%; */
  height: 530px;
  background: url(../assets/Contact-banner.jpg) no-repeat;
  background-size: cover;
  margin: auto;
}

.contactbanar img {
  width: 90%;
}
</style>
