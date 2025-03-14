<script setup lang="ts">

</script>

<template>
  <div class="p-8 mt-6 lg:mt-0 rounded bg-gradient-to-br from-zinc-900 to-red-500 w-screen h-screen">

    <form>

      <div class="md:flex mb-6">
        <div class="md:w-1/3">
          <label class="block text-white font-bold md:text-left mb-3 md:mb-0 pr-4" for="my-textfield">
            موضوع
          </label>
        </div>
        <div class="md:w-2/3">
          <input class="form-input block w-full bg-transparent placeholder:text-white text-white text-sm border border-white rounded-md px-3 py-2 transition duration-300 ease focus:outline-none focus:border-slate-400 hover:border-slate-300 shadow-sm focus:shadow" id="my-textfield" type="text" value="">
          <p class="py-2 text-sm text-white">موضوعی که می خواهید در مورد آن بنویسید را وارد کنید.</p>
        </div>
      </div>


      <div class="md:flex mb-6">
        <div class="md:w-1/3">
          <label class="block text-white font-bold md:text-left mb-3 md:mb-0 pr-4" for="my-textarea">
            خاطرات خود را بنویسید
          </label>
        </div>
        <div class="md:w-2/3">
          <textarea class="form-textarea block w-full bg-transparent placeholder:text-white text-white text-sm border border-white rounded-md px-3 py-2 transition duration-300 ease focus:outline-none focus:border-slate-400 hover:border-slate-300 shadow-sm focus:shadow" id="my-textarea" rows="27"></textarea>
        </div>
      </div>

      <div class="md:flex justify-items-center items-center">
        <div class="md:w-1/3"></div>
        <div class="md:w-2/3 flex flex-col gap-5">
          <button class="shadow bg-white hover:bg-yellow-500 focus:shadow-outline focus:outline-none text-black font-bold py-2 px-4 rounded" type="button">
            دخیره خاطرات
          </button>
          <button class="shadow bg-white hover:bg-yellow-500 focus:shadow-outline focus:outline-none text-black font-bold py-2 px-4 rounded" type="button">
            <NuxtLink to="/home-page">بازگشت به صفحه خانه</NuxtLink>
          </button>
        </div>
      </div>
    </form>

  </div>
</template>

<style scoped>
*
{
  direction: rtl;
}
</style>