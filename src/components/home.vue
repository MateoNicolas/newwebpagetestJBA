<script setup>
import { ref } from 'vue';

defineProps({
  msg: String,
});
</script>

<template>
 <h1>{{ msg }}</h1>
  <div class="hello">   
    <div class="menu">
    <div class="menu-item">Acerca</div>
    <div class="menu-item">Contribuye</div>
    <div class="menu-item">Productos</div>
    <div class="menu-item">Blog</div>
    <div class="menu-item">Contacto</div>
    </div>
  </div>
  <div class="card">"Hasta los negocios debían tener una postura escénica pintoresca." <br> Oscar Wilde </div>

  
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
.menu {
  display: flex;
  align-items: center;
  justify-content: space-around;
  
}
.menu-item{
  flex:1;
  font-weight: 700;
  margin: 10px;
  text-align: center;
  
}
</style>
