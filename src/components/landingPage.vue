<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});
</script>

<template>
  <span class="msg"> PROXIMAMENTE </span>
  <br />
  <span class="logo"> 
  <img src="../assets/IMG_0109.jpg" alt="logo">
   </span>
  <br />
  <span class="social-media">
    Follow us, meanwhile:
    <div class="menu">
      <div class="social-item">
        <a href="www.instagram.com"
          ><img
            src="../assets/instagram.jpg"
            alt="instagram logo"
            style="width: 42px; height: 42px"
        /></a>
      </div>
    </div>
  </span>
</template>

<style scoped>
.msg {
  color: black;
}
.logo {
  background: white;
}
.social-media {
}
</style>
