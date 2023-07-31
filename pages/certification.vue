
<template>
  <!-- hero -->
  <section class="py-12 mx-20">
    <div class="w-full px-12 py-2 flex justify-between items-center space-x-4">
      <img src="/hero-6.svg" class="w-1/2" alt="" />
      <h1
        class="text-center font-semibold w-full lg:w-1/2 text-gray-700 text-3xl lg:text-6xl lg:leading-relaxed lg:px-8"
      >
        Sertifikasi
      </h1>
    </div>

    <!-- main hero -->
    <div class="flex justify-center py-8">
      <img src="/404.svg" alt="" srcset="" />
    </div>

    <div>
      <p class="text-center px-8 py-10 text-light text-sm lg:text-base">
        Mohon maaf, halaman ini sedang dalam tahap pengembangan, silahkan
        hubungi tim pengembang untuk info lebih lanjut.
      </p>

      <div class="flex justify-center space-x-6">
        <NuxtLink
          to="/"
          class="bg-[#03989E] text-white font-semibold text-sm lg:text-base rounded-full px-3 py-2 lg:px-6 lg:py-4 outline-[#03989E]"
        >
          Kembali ke beranda
        </NuxtLink>
      </div>
    </div>
  </section>
</template>