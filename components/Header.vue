<template>
  <div class="mx-6 lg:mx-20">
    <div class="flex justify-between items-center px-4 lg:px-8 pt-14">
      <div>
        <NuxtLink to="/">
          <img src="/logo.svg" alt="" srcset="" />
        </NuxtLink>
      </div>
      <div class="lg:hidden text-right">
        <img src="/hamburger.svg" alt="" />
      </div>
      <div class="hidden lg:flex justify-end space-x-6">
        <NuxtLink to="/">
          <div class="px-4 py-2 font-bold">Home</div>
        </NuxtLink>
        <div class="px-4 py-2">Service</div>
        <div class="px-4 py-2">Profile</div>
        <div class="px-4 py-2">Login</div>
      </div>
    </div>
  </div>
</template>