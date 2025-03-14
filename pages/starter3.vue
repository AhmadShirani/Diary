<script setup lang="ts">

</script>

<template>
  <div class="bg-gradient-to-br from-zinc-900 to-red-500 w-screen h-screen flex items-center justify-center flex-col text-center">
    <div>
      <nuxt-link to="/login-or-sign-up"><p class="absolute top-6 right-6 text-sm  text-white px-2 py-2 rounded">رد شدن</p></nuxt-link>
    </div>
    <div>
      <p>با ثبت نام در بیست من خانواده بیست آفاق  را گسترش دهید و این یعنی افزایش روحیه تیمی و آگاهی داشتن و زندگی کردن با این عقیده و باور که موفقیت یک گروه به مراتب برزگتر عمیق تر و بهتر از موفقیت فردی خواهد بود.</p>
    </div>
    <div class="w-screen text-xs fixed bottom-10 left-0 flex justify-center text-white">
      <span class="w-2.5 h-2.5 inline-block bg-white rounded-full mr-2"></span>
      <nuxt-link to="/starter2"> <span class="w-2.5 h-2.5 inline-block bg-gray-400 rounded-full mr-2"></span></nuxt-link>
      <nuxt-link to="/starter"><span class="w-2.5 h-2.5 inline-block bg-gray-400 rounded-full mr-2"></span></nuxt-link>
    </div>
    <div class="absolute flex bottom-6 left-6 text-white px-2 py-2">
      <nuxt-link to="/starter2"><p>قبلی</p></nuxt-link>
    </div>
    <div class="absolute flex  bottom-6 right-6  text-white px-2 py-2 rounded">
      <nuxt-link to="/login-or-sign-up"><p>بعدی</p></nuxt-link>
    </div>
  </div>
</template>

<style scoped>
*
{
  direction: rtl;
}
</style>