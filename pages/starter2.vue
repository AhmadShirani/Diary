<script setup lang="ts">

</script>

<template>
  <div class=" w-screen h-screen flex items-center justify-center flex-col text-center">
    <img src="/public/img/louii.jpg" alt="bg" class="absolute top-0 left-0 w-full h-full object-cover">
     
    <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-center text-white">
      <span class="text-sm font-mediume">    شرکت تجارت الکترونیک بیست آفاق برای کاربران واعضای تیم مجموعه مای بیست این امکان را فراهم کرده تا شما تجارب وخاطرات ارزشمند خود را در کمترین زمان ممکن و تنها با دسترسی به تلفن همراه ثبت کنید.</span>      
    </div>
    
    <div>
      <nuxt-link to="/login-or-sign-up"><p class="absolute top-6 right-6 text-sm  text-white px-2 py-2 rounded">رد شدن</p></nuxt-link>
    </div>
    
    <div>
      <p> شرکت تجارت الکترونیک بیست آفاق برای کاربران واعضای تیم مجموعه مای بیست این امکان را فراهم کرده تا شما تجارب وخاطرات ارزشمند خود را در کمترین زمان ممکن و تنها با دسترسی به تلفن همراه ثبت کنید.</p>
    </div>
    <div class="w-screen text-xs fixed bottom-10 left-0 flex justify-center text-white">
      <nuxt-link to="/starter3"> <span class="w-2.5 h-2.5 inline-block bg-gray-400 rounded-full mr-2"></span></nuxt-link>
      <span class="w-2.5 h-2.5 inline-block bg-white rounded-full mr-2"></span>
      <nuxt-link to="/starter"><span class="w-2.5 h-2.5 inline-block bg-gray-400 rounded-full mr-2"></span></nuxt-link>
    </div>
    <div class="absolute flex bottom-6 left-6 text-white px-2 py-2">
      <nuxt-link to="/starter"><p>قبلی</p></nuxt-link>
    </div>
    <div class="absolute flex  bottom-6 right-6  text-white px-2 py-2 rounded">
      <nuxt-link to="/starter3"><p>بعدی</p></nuxt-link>
    </div>
  </div>
</template>

<style scoped>
*
{
  direction: rtl;
}
</style>

