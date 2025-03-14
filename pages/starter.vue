<script setup lang="ts">

</script>

<template>
  <div class="bg-gradient-to-br from-zinc-900 to-red-500 w-screen h-screen flex items-center justify-center flex-col text-center">
    <div>
      <p>خاطرات ماندگار در بیست آفاق</p>
      <p>LASTING MEMORIES IN 20VISION</p>
    </div>
    <div>
      <nuxt-link to="/login-or-sign-up"><p class="absolute top-6 right-6 text-sm  text-white px-2 py-2 rounded">رد شدن</p></nuxt-link>
    </div>
    <div>
      <div class="w-screen text-xs fixed bottom-10 left-0 flex justify-center text-white">
        <nuxt-link to="/starter3"> <span class="w-2.5 h-2.5 inline-block bg-gray-400 rounded-full mr-2"></span></nuxt-link>
        <nuxt-link to="/starter2"><span class="w-2.5 h-2.5 inline-block bg-gray-400 rounded-full mr-2"></span></nuxt-link>
        <span class="w-2.5 h-2.5 inline-block bg-white rounded-full mr-2"></span>
      </div>
    </div>
    <div class="absolute flex  bottom-6 right-6  text-white px-2 py-2 rounded">
      <nuxt-link to="/starter2"><p>بعدی</p></nuxt-link>
    </div>
  </div>
</template>



<style>
*
{
  direction: rtl;
}
</style>