<script setup lang="ts">

</script>

<template>
  <div class="relative w-screen h-screen">
    <img src="/public/img/ali.jpg" class="absolute top-0 left-0 w-full h-full object-cover">
    
    
    <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-center text-white">
      <span class="text-lg font-bold">خاطرات ماندگار در بیست آفاق</span>
      <br>
      <span class="text-sm">LASTING MEMORIES IN 20VISION</span>
    </div>

    
    <nuxt-link to="/login-or-sign-up">
      <p class="absolute top-6 right-6 text-sm text-white px-2 py-2 rounded">رد شدن</p>
    </nuxt-link>
    
    <div class="absolute bottom-10 left-0 w-screen flex justify-center text-white text-xs">
      <nuxt-link to="/starter3">
        <span class="w-2.5 h-2.5 inline-block bg-gray-400 rounded-full mr-2"></span>
      </nuxt-link>
      <nuxt-link to="/starter2">
        <span class="w-2.5 h-2.5 inline-block bg-gray-400 rounded-full mr-2"></span>
      </nuxt-link>
      <span class="w-2.5 h-2.5 inline-block bg-white rounded-full mr-2"></span>
    </div>

    <nuxt-link to="/starter2">
      <p class="absolute bottom-6 right-6 text-white px-2 py-2 rounded">بعدی</p>
    </nuxt-link>
  </div>
</template>




<style>
*
{
  direction: rtl;
}
</style>