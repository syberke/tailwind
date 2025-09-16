<template>

    <Header />
  
      <Banners />
      <Content />
      <Product/>
      <Content1 />
      <Contact />
      <Footer />

</template>

<script setup>
import Header from './components/navbar/Navbar.vue'
import Content from './components/Content.vue'
import Content1 from './components/Content1.vue'
import Contact from './components/Contact/Contact.vue'
import Banners from './components/Banners.vue'
import Product from './components/product/Product.vue'
import Footer from './components/footer/Footer.vue'
</script>
