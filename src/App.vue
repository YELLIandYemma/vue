<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import login from './components/login.vue';
</script>

<template>
  <div class="container">
    <div class="text-title">
      <h1><strong>Learn to code by <br/>  watching others </strong></h1>
    </div><br/>
    <div>
      <div>
        <span>
          See how expirienced devolpers solve problems in real-time<br/>
          Watching scripted tutorials is great but, understanding how<br/>
          devolpers think
        </span>
      </div>
    </div>
  </div>

  <login/>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
  body{
    background-image: url('../public/bg-intro-desktop.png');
    background-color: #ff7a7a;
    font-family:'Poppins', sans-serif;
  }

  .container{
    position: absolute;
    top:50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color:white
  }

</style>



