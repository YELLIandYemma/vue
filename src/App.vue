<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import login from './components/login.vue';
</script>

<template>
  <login/>

</template>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap");
  body{
    background-image: url('../public/bg-intro-desktop.png');
    background-color: #ff7a7a;
    
  }
</style>



