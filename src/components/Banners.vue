<template>
  <section class="relative lg:h-screen lg:place-content-center overflow-hidden">

    <!-- Video Background -->
    <video
      autoplay
      loop
      muted
      playsinline
      class="absolute inset-0 w-full h-full object-cover"
    >
      <source src="/Nike Japan’s Air Max Day (2022).mp4" type="video/mp4" />
      Browser kamu tidak mendukung video HTML5.
    </video>

    <!-- Overlay gelap -->
    <div class="absolute inset-0 bg-black/40"></div>

    <!-- Konten -->
    <div class="relative mx-auto w-screen max-w-screen-xl px-4 py-16 sm:px-6 sm:py-24 lg:px-8 lg:py-32">
      <div class="mx-auto max-w-prose text-center text-white">
        <h1 class="text-4xl font-bold sm:text-5xl">
          Belanja Mudah, Cepat, dan
          <strong class="text-indigo-300"> Aman </strong>
        </h1>

        <p class="mt-4 text-base text-pretty sm:text-lg/relaxed">
          Temukan ribuan produk pilihan dari brand terbaik, dengan harga terjangkau dan pengiriman super cepat langsung ke depan pintu Anda.
        </p>

        <div class="mt-4 flex justify-center gap-4 sm:mt-6">
          <a
            class="inline-block rounded border border-indigo-600 bg-indigo-600 px-5 py-3 font-medium text-white shadow-sm transition-colors hover:bg-indigo-700"
            href="#produk"
          >
            Belanja Sekarang
          </a>

          <a
            class="inline-block rounded border border-white/30 px-5 py-3 font-medium text-white shadow-sm transition-colors hover:bg-white/10 hover:text-white"
            href="#tentang"
          >
            Pelajari Lebih Lanjut
          </a>
        </div>
      </div>
    </div>
  </section>
</template>
