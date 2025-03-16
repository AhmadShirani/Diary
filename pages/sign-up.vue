<script setup lang="ts">
const router = useRouter();

const username = ref<String>("");
const password = ref<String>("");
const rePassword = ref<String>("");


const doRegister = () => {
  if (username.value == "") alert('Enter Username ...')
  else if (password.value == "") alert('Enter password ...')
  else if (rePassword.value == "") alert('Enter rePassword ...')
  else if (password.value != rePassword.value) alert('Password And RePassword Are Not Matched , Fix It ...')
  else{
    alert ('Success , Send To Server')
    router.push("/"); // مسیر صفحه بعدی
  } 
}

</script>

<template>
  <div class="bg-gradient-to-br from-zinc-900 to-red-500 w-screen h-screen flex items-center justify-center flex-col text-center">
    <div class="grid gap-5 my-5">
      <div class="border-b-4 border-white size-11">
        <h1 class="my-1 ml-50">ورود</h1>
      </div>

      <label class="ml-52">نام کاربری </label>
      <input v-model="username" class="w-full bg-transparent placeholder:text-grey-700 text-white text-sm border border-white rounded-md px-3 py-2 transition duration-300 ease focus:outline-none focus:border-slate-400 hover:border-slate-300 shadow-sm focus:shadow"placeholder="نام" required>
      <label class="ml-52">رمز عبور</label>
      <input v-model="password" class="w-full bg-transparent placeholder:text-grey-700 text-white text-sm border border-white rounded-md px-3 py-2 transition duration-300 ease focus:outline-none focus:border-slate-400 hover:border-slate-300 shadow-sm focus:shadow "placeholder="•••••••••" required type="password">
      
        <label for="confirm_password" class="block ml-48 mb-2 text-sm  text-white dark:text-white ">تایید رمز عبور</label>
        <input v-model="rePassword" type="password" id="confirm_password" class="bg-transparent border 6 placeholder:text-grey-700 border-white text-white text-sm  rounded-md px-3 py-2 transition duration-300 ease focus:outline-none focus:border-slate-400 hover:border-slate-300 shadow-sm focus:shadow" placeholder="•••••••••" required />
   
    </div>
    <div class="mt-12">
      <button @click="doRegister" class="bg-white text-black font-bold py-2 px-14 rounded-full">ورود</button>
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