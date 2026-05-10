<template>
  <main class="max-w-7xl mx-auto px-4 lg:px-6">
    <HeroSection />
    <PromoBanners />
    <FeaturedProducts />
    <MosaicPromo />
    <CategoriesList />
    <Newsletter />
  </main>
</template>

<script setup>
import HeroSection from '../components/HeroSection.vue'
import PromoBanners from '../components/PromoBanners.vue'
import FeaturedProducts from '../components/FeaturedProducts.vue'
import MosaicPromo from '../components/MosaicPromo.vue'
import CategoriesList from '../components/CategoriesList.vue'
import Newsletter from '../components/Newsletter.vue'
</script>
