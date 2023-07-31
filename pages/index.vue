<template>
  <!-- hero -->
  <section class="py-12 mx-20">
    <div class="w-full lg:px-12 py-2">
      <h1
        class="font-semibold text-center text-gray-700 text-3xl lg:text-7xl lg:leading-loose"
      >
        Solusi dari segala permasalahan ternak
      </h1>
    </div>

    <!-- main hero -->
    <div class="flex justify-center py-6 lg:py-8">
      <img src="/hero.svg" alt="" srcset="" />
    </div>

    <div>
      <p class="text-center px-8 py-6 lg:py-10">
        Jupiter (Juru Pinter Ternak) Berkomitmen untuk membantu peternak yang
        fokus pada kesehatan ternak, edukasi<br />
        dan pengembangan ternak, serta sertifikasi
      </p>

      <div class="flex justify-center space-x-6">
        <NuxtLink
          to="/register"
          class="bg-[#03989E] text-white font-semibold text-center text-sm lg:text-base rounded-full px-3 py-2 lg:px-6 lg:py-4 outline outline-[#03989E]"
        >
          Daftar Gratis
        </NuxtLink>
        <NuxtLink
          to="/consultation"
          class="bg-white text-[#03989E] font-semibold text-center text-sm lg:text-base rounded-full px-3 py-2 lg:px-6 lg:py-4 outline outline-[#03989E]"
        >
          Coba TernAI
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- program -->
  <section class="lg:py-12 mt-6 mx-20">
    <div class="w-full px-12 py-2">
      <h1
        class="font-semibold text-center text-gray-700 text-3xl lg:text-5xl leading-relaxed"
      >
        Program kami
      </h1>

      <p class="text-center mt-8 lg:mt-12">
        Unggul pada aspek penting dalam beternak, Kami percaya bahwa inovasi dan
        teknologi adalah kunci untuk mencapai keberhasilan
      </p>
    </div>

    <div class="my-10 lg:px-12">
      <div class="lg:flex lg:justify-start lg:space-x-3 mb-3">
        <NuxtLink
          to="/doctor"
          class="w-full lg:w-1/2 flex rounded-2xl shadow-lg mb-3 lg:mb-0"
        >
          <img
            src="/1.svg"
            alt=""
            class="w-28 lg:w-56 rounded-l-2xl"
            srcset=""
          />
          <div
            class="lg:w-1/2 w-full bg-[#03989E] text-white flex items-center justify-center flex-col rounded-r-2xl"
          >
            <img src="/icon-1.svg" class="w-10 lg:w-16 text[#03989E]" alt="" />
            <h1
              class="text-lg lg:text-4xl font-semibold lg:font-bold lgpx-6 text-center lg:my-4"
            >
              Dokter Hewan Online
            </h1>
          </div>
        </NuxtLink>
        <NuxtLink
          to="/consultation"
          class="w-full lg:w-1/2 flex rounded-2xl shadow-lg"
        >
          <img
            src="/3.svg"
            alt=""
            class="w-28 lg:w-56 rounded-l-2xl"
            srcset=""
          />
          <div
            class="lg:w-1/2 w-full bg-[#545454] text-white flex items-center justify-center flex-col rounded-r-2xl"
          >
            <img src="/icon-3.svg" class="w-10 lg:w-16 text[#545454]" alt="" />
            <h1
              class="text-lg lg:text-4xl font-semibold lg:font-bold lgpx-6 text-center lg:my-4"
            >
              Konsultasi AI
            </h1>
          </div>
        </NuxtLink>
      </div>

      <div class="lg:flex lg:justify-start lg:space-x-3">
        <NuxtLink
          to="/e-course"
          class="lg:w-1/2 flex rounded-2xl shadow-lg mb-3 lg:mb-0"
        >
          <img
            src="/2.svg"
            alt=""
            class="w-28 lg:w-56 rounded-l-2xl"
            srcset=""
          />
          <div
            class="lg:w-1/2 w-full bg-[#7FB74A] text-white flex items-center justify-center flex-col rounded-r-2xl"
          >
            <img src="/icon-1.svg" class="w-10 lg:w-16 text[#7FB74A]" alt="" />
            <h1
              class="text-lg lg:text-4xl font-semibold lg:font-bold lgpx-6 text-center lg:my-4"
            >
              E-Course Peternakan
            </h1>
          </div>
        </NuxtLink>
        <NuxtLink
          to="/certification"
          class="lg:w-1/2 flex rounded-2xl shadow-lg"
        >
          <img
            src="/4.svg"
            alt=""
            class="w-28 lg:w-56 rounded-l-2xl"
            srcset=""
          />
          <div
            class="lg:w-1/2 w-full bg-[#FFAA00] text-white flex items-center justify-center flex-col rounded-r-2xl"
          >
            <img src="/icon-2.svg" class="w-10 lg:w-16 text[#FFAA00]" alt="" />
            <h1
              class="text-lg lg:text-4xl font-semibold lg:font-bold lgpx-6 text-center lg:my-4"
            >
              Sertifikasi
            </h1>
          </div>
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- keunggulan -->
  <section class="py-12 lg:px-20 mt-6 mx-20">
    <div class="lg:flex justify-between space-x-6">
      <div class="lg:px-6 lg:py-8 lg:w-1/2 flex justify-center">
        <img src="/tani.svg" width="457px" alt="" />
      </div>
      <div class="lg:w-1/2">
        <h1
          class="font-semibold text-gray-700 text-3xl text-center lg:text-left mb-3 lg:mb-6 lg:text-5xl leading-relaxed"
        >
          Mengapa memilih kami?
        </h1>

        <p class="text-justify">
          Unggul pada aspek penting dalam beternak, Kami percaya bahwa inovasi
          dan teknologi adalah kunci untuk mencapai keberhasilan
        </p>

        <div class="flex flex-col space-y-4 mt-12">
          <div class="flex justify-start items-start space-x-3">
            <img class="hidden lg:block" src="/feat-1.svg" alt="" />
            <div>
              <div class="flex items-center space-x-2 lg:space-x-0">
                <img class="w-8 lg:hidden" src="/feat-1.svg" alt="" />
                <h3 class="font-bold text-xl">Akses 24/7</h3>
              </div>
              <p>
                Dapat diakses kapan saja dan di mana saja. Anda memiliki
                fleksibilitas sesuai kebutuhan Anda sendiri.
              </p>
            </div>
          </div>
          <div class="flex justify-start space-x-3">
            <img class="hidden lg:block" src="/feat-2.svg" alt="" />
            <div>
              <div class="flex items-center space-x-2 lg:space-x-0">
                <img class="w-8 lg:hidden" src="/feat-2.svg" alt="" />
                <h3 class="font-bold text-xl">Teknologi AI</h3>
              </div>
              <p>
                Menerapkan Artificial Intelligence sebagai sarana konsultasi
                untuk Peternak
              </p>
            </div>
          </div>
          <div class="flex justify-start space-x-3">
            <img class="hidden lg:block" src="/feat-3.svg" alt="" />
            <div>
              <div class="flex items-center space-x-2 lg:space-x-0">
                <img class="w-8 lg:hidden" src="/feat-3.svg" alt="" />
                <h3 class="font-bold text-xl">Interaktif dan Praktis</h3>
              </div>
              <p>
                Cukup di satu platfom segala kebutuhan dan keperluan
                terfasilitasi dengan baik
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- testimonial -->
  <section class="py-12 mt-6 lg:px-20 mx-20">
    <div class="w-full px-12 py-2">
      <h1
        class="font-semibold text-center text-gray-700 text-3xl lg:text-5xl leading-relaxed"
      >
        Apa kata mereka
      </h1>
    </div>

    <div class="lg:flex justfy-start lg:space-x-4 mt-8">
      <div
        class="flex flex-col justify-between shadow-xl rounded-lg px-3 py-2 lg:px-6 lg:py-4 w-full lg:w-2/3"
      >
        <p class="font-thin mb-4 leading-loose py-6">
          Ketika sapi-sapi saya mengalami masalah kesehatan, saya bisa dengan
          cepat berkonsultasi dengan dokter hewan secara online, tanpa harus
          mengeluarkan biaya dan waktu untuk pergi ke klinik hewan. Pelayanan
          dari tim dokternya sangat profesional dan responsif. Terima kasih,
          website ini telah menyelamatkan hewan-hewan ternak saya!
        </p>
        <div class="flex justify-start items-center space-x-3">
          <img src="/profile-1.svg" alt="" />
          <div class="text-sm italic">
            <h3 class="font-bold">Budi</h3>
            <p>Peternak Sapi, Jawa Tengah</p>
          </div>
        </div>
      </div>
      <div
        class="flex flex-col justify-between shadow-xl rounded-lg px-3 py-2 lg:px-6 lg:py-4 w-full lg:w-2/3"
      >
        <p class="font-thin mb-4 leading-loose py-6">
          Saya tidak pernah menduga bahwa ada platform yang menyediakan dokter
          hewan dan kursus peternakan dalam satu tempat! Ini sangat praktis dan
          membantu sekali bagi kami para peternak. Saya seringkali mengalami
          kendala teknis dalam manajemen peternakan, dan fitur konsultasi AI-nya
          sangat membantu memberikan solusi instan.
        </p>
        <div class="flex justify-start items-center space-x-3">
          <img src="/profile-2.svg" alt="" />
          <div class="text-sm italic">
            <h3 class="font-bold">Hadi</h3>
            <p>Peternak Kambing, Kalimantan</p>
          </div>
        </div>
      </div>
      <div
        class="flex flex-col justify-between shadow-xl rounded-lg px-3 py-2 lg:px-6 lg:py-4 w-full lg:w-2/3"
      >
        <p class="font-thin mb-4 leading-loose py-6">
          Fitur dokter hewan online-nya benar-benar menyelamatkan hewan
          peliharaan saya dari beberapa kondisi kesehatan yang serius. Saya juga
          telah menyelesaikan beberapa kursus yang relevan dengan peternakan,
          dan mereka sangat membantu dalam mengasah keterampilan dan pengetahuan
          saya. Mendapatkan sertifikasi dari kursus-kursus tersebut juga
          memberikan kepercayaan diri ekstra dalam mencurahkan perhatian saya
          pada peternakan.
        </p>
        <div class="flex justify-start items-center space-x-3">
          <img src="/profile-3.svg" alt="" />
          <div class="text-sm italic">
            <h3 class="font-bold">Dian</h3>
            <p>Peternak Kelinci, NTT</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- campaign -->
  <section class="pt-12 mt-6 min-w-full bg-[url('/hero-2.svg')] bg-cover">
    <div class="w-full px-12 py-56 text-center">
      <h1
        class="font-semibold text-center text-white text-3xl lg:text-6xl leading-tight mb-8"
      >
        Mari bergabung bersama<br />
        kami sekarang!
      </h1>

      <NuxtLink
        to="/register"
        class="bg-[#03989E] text-white text-sm lg:text-base rounded-full px-3 py-2 lg:px-6 lg:py-4 outline outline-[#03989E]"
      >
        Daftar Gratis
      </NuxtLink>
    </div>
  </section>
</template>