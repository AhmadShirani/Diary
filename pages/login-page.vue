<script setup lang="ts">

</script>

<template>
  <div class="bg-gradient-to-br from-zinc-900 to-red-500 w-screen h-screen flex items-center justify-center flex-col text-center">
    <div class="grid gap-5 my-5">
      <div class="border-b-4 border-white size-11">
        <h1 class="my-3 ml-60">ورود</h1>
      </div>

      <label class="ml-52">نام کاربری</label>
      <input class="w-full bg-transparent placeholder:text-white text-white text-sm border border-white rounded-md px-3 py-2 transition duration-300 ease focus:outline-none focus:border-slate-400 hover:border-slate-300 shadow-sm focus:shadow">
      <label class="ml-52">رمز عبور</label>
      <input class="w-full bg-transparent placeholder:text-white text-white text-sm border border-white rounded-md px-3 py-2 transition duration-300 ease focus:outline-none focus:border-slate-400 hover:border-slate-300 shadow-sm focus:shadow">
    </div>
    <div class="mt-12">
      <button class="bg-white text-black font-bold py-2 px-14 rounded-full">ورود</button>
    </div>
    <div class="absolute flex bottom-6 left-6 text-white px-2 py-2">
      <nuxt-link to="/login-or-sign-up"><p>قبلی</p></nuxt-link>
    </div>
  </div>
</template>

<style scoped>
*
{
  direction: rtl;
}
</style>