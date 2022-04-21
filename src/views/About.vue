<script setup>
 import karyakarini from '../assets/KARYAKARANI.jpeg'
 import registration from '../assets/registration.jpg'
</script>

<template>
<div id="society">
    <h2 class="px-4 py-6 text-xl">Society Registration Certificate</h2>
    <img :src="registration" />
  </div>
  <div id="managment">
    <h2 class="px-4 py-6 text-xl">Management Committee</h2>
    <img :src="karyakarini" />
  </div>
</template>
