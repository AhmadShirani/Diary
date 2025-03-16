<script setup lang="ts">

</script>

<template>
  <div class="bg-gradient-to-br from-zinc-900 to-red-500 w-screen h-screen flex items-center justify-center flex-col gap-5 p-24">
  <nuxt-link to="/diary-writing-page">
    <div class="bg-white rounded-lg shadow-lg p-8">
      <div class="relative overflow-hidden">
        <img class="object-cover w-full h-full" src="/public/img/c4383f26-a9ac-4857-92d9-e4d49c904ec8.jpg" alt="Product">
        <div class="absolute inset-0 bg-black opacity-40"></div>
        <div class="absolute inset-0 flex items-center justify-center">
        </div>
      </div>
      <h3 class="text-xl font-bold text-gray-900 mt-4">نوشتن خاطرات</h3>
      <p class="text-gray-500 text-sm mt-2">در این قسمت می توانید خاطرات خود را بنویسید</p>
      <div class="flex items-center mt-4">
        <button class="bg-gray-900 text-white p-4 rounded-full font-bold hover:bg-gray-800 text-center">بزن بریم</button>
      </div>
    </div>
  </nuxt-link>
<nuxt-link to="">
  <div class="bg-white rounded-lg shadow-lg p-8">
    <div class="relative overflow-hidden">
      <img class="object-cover w-full h-full" src="/public/img/Photo_of_Library_001.jpg" alt="Product">
      <div class="absolute inset-0 bg-black opacity-40"></div>
      <div class="absolute inset-0 flex items-center justify-center">
      </div>
    </div>
    <h3 class="text-xl font-bold text-gray-900 mt-4">لیست خاطرات</h3>
    <p class="text-gray-500 text-sm mt-2">در این قسمت می توانید لیست خاطرات خود را مشاهده کنید</p>
    <div class="flex items-center mt-4">
      <button class="bg-gray-900 text-white p-4 rounded-full font-bold hover:bg-gray-800 text-center">بزن بریم</button>
    </div>
  </div>
</nuxt-link>
  </div>
</template>

<style scoped>
*
{
  direction: rtl;
}
</style>