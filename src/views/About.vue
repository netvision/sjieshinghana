<script setup>
 import lab from '../assets/lab1.jpg'
 import ground from '../assets/ground.jpg'
 import registration from '../assets/registration.jpg'
</script>

<template>
<div id="society">
    <h2 class="text-3xl mx-14 pt-16 pb-0 font-serif border-b-2 border-orange-500 w-10/12">Society Registration Certificate</h2>
    <img :src="registration" class="rounded-md p-5 border-2 m-16 w-10/12" />
  </div>
  <div id="managment">
    <h2 class="text-3xl mx-14 pt-16 pb-0 font-serif border-b-2 border-orange-500 w-10/12">Laboratory and Ground Photograph</h2>
    <img :src="lab" class="rounded-md p-5 border-2 m-16 w-8/12" />
    <img :src="ground" class="rounded-md p-5 border-2 m-16 w-8/12" />
  </div>
</template>
