<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});
</script>

<template>
<span class="msg">
PROXIMAMENTE
</span>
<br>
<span class="logo">
JAVIER BRAVO, ARTISTA
</span>
<br>
<span class="social-media">
Follow us, meanwhile:
<div class="menu">
    <div class="social-item">
    
<a href="instagram.com"><img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;"></a>
    </div>
    
  </div>
</span>


</template>

<style scoped>
.msg{
  color: white;
}
.logo{
  background: white;
}
.social-media{

}

</style>
