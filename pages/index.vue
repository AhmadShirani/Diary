<script>
export default {
  mounted() {
    // پس از 3 ثانیه، تغییر مسیر به صفحه جدید
    setTimeout(() => {
      this.$router.push("/starter"); // مسیر صفحه بعدی
    }, 3000);
  },
};
</script>

<template>

  <div class="bg-gradient-to-br from-zinc-900 to-red-500 w-screen h-screen flex items-center justify-center flex-col text-center">
    <img class="ml-7 w-48" src="D:\Ahmad\Ahmad Shirani\project\Diary\public\img\Screenshot_18-2-2025_13534_ (1).png" alt="logo">
   <div class="">
     <p>20VISIONS DIARY</p>
     <p class="text-xs mt-2">دفترجه خاطرات بیست آفاق</p>
   </div>
    <div  class="button-0 mt-300 absolute bottom-0 left-50 mb-12">
      <p>VERSION 1.20</p>
    </div>
  </div>


</template>

<style>
  *
  {
    direction: rtl;
  }
</style>