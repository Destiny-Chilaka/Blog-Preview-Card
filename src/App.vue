<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>



<template>
  <div class="figtree flex items-center justify-center h-screen bg-[#f4e04d] p-4">
   <div class="bg-white p-5 rounded-xl shadow-[8px_8px_0_0_#222] w-[384px] border-1 border-black ">
    <img src="./assets/Blog-Image.png" alt="Code block" class="mb-7 w-full">
      <p class="text-black inline-block font-sans bg-[#f4e04d] mb-4 font-bold  text-base py-1  px-3.5 rounded">Learning</p>
      <p class="text-[14px] sm:text-[15px] mb-4">Published 21 Dec 2023</p>
      <h2 class="font-bold sm:text-2xl mb-4 text-xl ">HTML & CSS foundations</h2>
      <p class="text-[14px] sm:text-[15px] text-gray-500 mb-4 inter">These languages are the backbone of every website, defining structure, content, and presentation.</p>
      <div class="flex items-center space-x-3 mt-6">
     <img src="./assets/profile-pic.avif" alt="Profile" class="w-8 h-8 rounded-full object-cover" />
    <span class="font-bold text-sm text-black">Greg Hooper</span>
  </div>
    </div>
  </div>
</template>

<style scoped>
</style>

