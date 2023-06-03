<template>
  <div>
    <div class="flex justify-between p-5 sm:hidden">
      <div><img src="/images/3esLogo.svg" /></div>
      <div @click="$emit('base-slide-panel')">
        <img src="/icons/menuIcon.svg" />
      </div>
    </div>
    <div class="hidden sm:block relative p-5 xl:p-7">
      <div class="flex w-full bg-white items-center">
        <div
          class="flex text-sm text-black flex-1 justify-end space-x-4 xl:space-x-10 xl:text-base"
        >
          <NuxtLink to="/">Our Products</NuxtLink>
          <NuxtLink to="about-us">For Engineers</NuxtLink>
          <NuxtLink to="/solutions">Multi-Vitamins</NuxtLink>
          <NuxtLink to="/workflow">Buy</NuxtLink>
          <NuxtLink to="/contact-us">Book</NuxtLink>
        </div>
        <div class="w-30 flex justify-center bg-slate-300 mx-12 lg:mx-16 rounded-sm">
          <button
            class="bg-esCyan px-4 py-1 text-sm rounded-full text-black xl:text-base xl:px-6"
          >
            SignIn / SignUp
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup></script>
<style>

</style>
