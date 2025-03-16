<script setup lang="ts">
import { NuxtLink } from '#components';


</script>

<template>

    

  <div class="bg-gradient-to-br from-red-800 to-slate-900 w-screen h-screen flex flex-col justify-center items-center text-center  ">
    <img class="w-60" src="D:\Ahmad\Ahmad Shirani\project\Diary\public\img\Screenshot_18-2-2025_13534_ (1).png">
    <hr class="w-80 h-0.5 mx-auto my-4 bg-white border-0 rounded-sm md:my-10 dark:bg-white">
   <span class=" text-lg text-center" > کاربر گرامی به بیست آفاق خوش آمدید</span>
   <span class=" text-lg text-center mt-3" >برای ثبت نام/ورود اقدام نمایید</span>
   
   
   <NuxtLink to="/login-page" class="text-white flex justify-center items-center bg-none border border-white focus:outline-none hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 font-medium rounded-full text-sm w-36 px-8 py-2.5 me-2 mb-2 dark:bg-none dark:text-white dark:border- dark:hover:bg-gray-700 dark:hover:border-gray-600 dark:focus:ring-gray-700 mt-20">
    <span>ورود</span>
   </NuxtLink>


    <NuxtLink to="/sign-up" class="text-white  flex justify-center items-center bg-none border border-white focus:outline-none hover:bg-gray-100 focus:ring-4 focus:ring-gray-100 font-medium rounded-full text-sm w-36 px-8 py-2.5 me-2 mb-2 dark:bg-none dark:text-white dark:border- dark:hover:bg-gray-700 dark:hover:border-gray-600 dark:focus:ring-gray-700 mt-8">
      <span>ثبت نام</span>
    </NuxtLink>   

     </div>
</template>

<style scoped>
*
{
  direction: rtl;
}

</style>