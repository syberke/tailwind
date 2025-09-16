<template>
  <div class="container mx-auto flex flex-wrap text-gray-700 font-bold text-3xl px-5">
    <h1>Product</h1>
  </div>

  <section class="text-gray-600 body-font bg-cover bg-center bg-fixed">
    <div class="bg-white/70 backdrop-blur-sm">
      <div class="container px-5 py-24 mx-auto">
        <div class="flex flex-wrap -m-4">

        
          <div
            v-for="i in 8"
            :key="i"
            class="lg:w-1/4 md:w-1/2 p-4 w-full"
          >
            <div
              class="rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300 bg-white"
            >
              <a class="block relative h-48 rounded-t-lg overflow-hidden">
                <img
                  alt="ecommerce"
                  class="object-cover object-center w-full h-full block"
                  src="https://sportaways.com/media/catalog/product/cache/cd7c6c71a47e90564e17811b95cac4e3/a/s/asics_gel_kayano_30_1011b548-300_-_dark_jadeblack_1.jpg"
                />
              </a>
              <div class="mt-4 px-4 pb-4 text-black">
                <h3 class="text-xs tracking-widest title-font mb-1">CATEGORY</h3>
                <h2 class="title-font text-lg font-medium">The Catalyzer</h2>
                <p class="mt-1">$16.00</p>
              </div>
            </div>
          </div>
    

        </div>
      </div>
    </div>
  </section>
</template>
