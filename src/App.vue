<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- <h1 class="text-3xl font-bold underline">
    HI DOES THIS WORK!
  </h1> -->
  <div class="p-10 from-indigo-100 to-yellow-100 md:flex md:item-center md:justify-items">
    <img src="/public/image.jpg" alt="" class="w-1/2 p-5">
    <table class="border border-solid border-black">
    <tr class="border border-solid border-black">
      <td colspan="2">Student Information</td>
    </tr>
    <tr class="border border-solid border-black">
      <td class="p-2 border border-solid border-black">Name</td>
      <td class="p-2 border border-solid border-black">Qasreena</td>
    </tr>
    <tr class="border border-solid border-black">
      <td class="p-2 border border-solid border-black">Student Id</td>
      <td class="p-2 border border-solid border-black">21FTT1281</td>
    </tr>
    <tr class="border border-solid border-black">
      <td class="p-2 border border-solid border-black">Course</td>
      <td class="p-2 border border-solid border-black">Diploma in Web Development</td>
    </tr>
  </table>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
