<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});
</script>

<template>
  <h1 class="msg"> PRONTO </h1>
  <h2>2023</h2>
  <br />

  <span class="social-media">
   <!-- 
    Follow us:
   
<div class="menu">
      <div class="social-item">
        <a href="www.instagram.com"
          ><img
            src="../assets/instagramQR.jpg"
            alt="instagram logo"
            style="width: 300px; height: 300px"
        /></a>
      </div>
    </div>

    -->
    
  </span>
</template>

<style scoped>
.msg {
  color: black;
  font-weight: 700px;
   
}

</style>
