<template>
<div class="flex">
  <div class="p-6 w-5/12">
    <img :src="geotag" class="p-6 m-6">
  </div>
  <div id="contact">
    <h2 class="text-3xl mx-14 pt-16 pb-0 font-serif border-b-2 border-orange-500 w-10/12">Contact Us</h2>
    <p class="text-xl w-10/12 text-left mx-16 pt-16">Principal</p>
    <p class="text-xl w-10/12 text-left mx-16 pt-5 pb-2 font-bold text-blue-900">Sharvani Jhajharia Institute of Education</p>
    <p class="text-xl w-10/12 text-left mx-16 pb-12">Mankro Road, Singhana - 333516, Jhunjhunu, Rajasthan</p>
    <p class="text-xl w-10/12 text-left mx-16 pb-12">Lat-Lon: 28.097291, 75.816395</p>
    <p class="text-xl w-10/12 text-left mx-16 pb-24">Phone: 01593-222697</p>
    <p class="text-xl w-10/12 text-left mx-16 pb-24">Email Id: <a href="mailto:sharvaniji@gmail.com">sharvaniji@gmail.com</a></p>
  </div>
</div>
</template>
<script setup>
import geotag from '../assets/geotag.jpg'
</script>