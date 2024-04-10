<template>
<h2 class="container w-full p-5 text-xl">Please click below to view the documents</h2>
<div class="container w-full flex mx-auto p-6 pl-0">
  <p class="align-left w-1/3 text-blue-800 hover:text-cyan-600 hover:bg-yellow-200 p-5 rounded-lg m-5"><a :href="committee" target="_blank"><img :src="pdf" class="w-14" /><span>Executive Committee</span></a></p>
  <p class="align-left w-1/3 text-blue-800 hover:text-cyan-600 hover:bg-yellow-200 p-5 rounded-lg m-5"><a :href="land" target="_blank"><img :src="pdf" class="w-14" /><span>Land Transformation</span></a></p>
<p class="align-left w-1/3 text-blue-800 hover:text-cyan-600 hover:bg-yellow-200 p-5 rounded-lg m-5"><a :href="ncte" target="_blank"><img :src="pdf" class="w-14" /><span>State NOC</span></a></p>
<p class="align-left w-1/3 text-blue-800 hover:text-cyan-600 hover:bg-yellow-200 p-5 rounded-lg m-5"><a :href="extention" target="_blank"><img :src="pdf" class="w-14" /><span>DCE Extention Letter</span></a></p>
<p class="align-left w-1/3 text-blue-800 hover:text-cyan-600 hover:bg-yellow-200 p-5 rounded-lg m-5"><a :href="affiliation" target="_blank"><img :src="pdf" class="w-14" /><span>PDU Affiliation Extention Letter</span></a></p>
</div>
</template>
<script setup>
import ncte from '../assets/STATE NOC.pdf'
import extention from '../assets/dce-extention.pdf'
import affiliation from '../assets/pdu-extention.pdf'
import committee from '../assets/executive-committee.pdf'
import land from '../assets/land.pdf'
import pdf from '../assets/pdf17.svg'

</script>