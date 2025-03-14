<script setup lang="ts">

</script>

<template>
  <div class="bg-gradient-to-br from-zinc-900 to-red-500 w-screen h-screen flex items-center justify-center flex-col text-center">
    <div>
      <p>.کاربر گرامی به بیست من خوش آمدید برای ثبت نام/ ورود اقدام کنید</p>
    </div>
    <nuxt-link to="/login-page">
      <div class="mt-12">
        <button class="bg-white text-black font-bold py-2 px-14 rounded-full">ثبت نام</button>
      </div>
    </nuxt-link>
    <div class="mt-12">
      <nuxt-link to="/sign-up">
        <button class="bg-white text-black font-bold py-2 px-14 rounded-full"> صفخه ورود</button>
      </nuxt-link>
    </div>
    <div class="absolute flex bottom-6 left-6 text-white px-2 py-2">
      <nuxt-link to="/starter3"><p>قبلی</p></nuxt-link>
    </div>
  </div>
</template>

<style scoped>
*
{
  direction: rtl;
}
</style>