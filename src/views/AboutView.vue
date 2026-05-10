<template>
  <main class="w-full overflow-hidden">
    <!-- Hero Section -->
    <section class="flex flex-col lg:flex-row min-h-[600px] border-b border-gray-100">
      <!-- Left Content -->
      <div class="w-full lg:w-1/2 bg-[#f8f4f2] flex flex-col justify-center p-12 lg:p-24 order-2 lg:order-1">
        <p class="text-[10px] font-bold uppercase tracking-[0.2em] text-[#ff8a8a] mb-4">Latest Collection</p>
        <h1 class="serif-font text-5xl lg:text-7xl font-bold text-gray-900 mb-8 leading-[1.1]">
          Lookbook<br>collection 2021
        </h1>
        <p class="text-gray-500 text-sm leading-relaxed max-w-md mb-10">
          We believe in a world where you have total freedom to be you, without judgement. To experiment. To express yourself. To be brave and grab life as the extraordinary adventure it is.
        </p>
        <div>
          <button class="bg-[#111] hover:bg-[#ff8a8a] text-white px-10 py-4 rounded-full font-bold text-[11px] uppercase tracking-widest transition-colors duration-300">
            Shop Now <i class="fas fa-arrow-right ml-2 text-[10px]"></i>
          </button>
        </div>
      </div>
      <!-- Right Image Slider -->
      <div class="w-full lg:w-1/2 h-[400px] lg:h-auto order-1 lg:order-2 relative overflow-hidden">
        <transition-group name="fade">
          <img v-for="(img, index) in slides" 
               :key="img" 
               v-show="currentSlide === index"
               :src="img" 
               alt="Beauty Collection" 
               class="absolute inset-0 w-full h-full object-cover">
        </transition-group>
        
        <!-- Slider Navigation -->
        <div class="absolute bottom-6 left-0 right-0 flex justify-center space-x-3 z-10">
          <button v-for="(_, index) in slides" :key="index"
                  @click="currentSlide = index"
                  class="w-2.5 h-2.5 rounded-full transition-colors duration-300 border border-white/30"
                  :class="currentSlide === index ? 'bg-[#ff8a8a] scale-125 border-[#ff8a8a]' : 'bg-white/60 hover:bg-white'"></button>
        </div>
      </div>
    </section>

    <!-- Core Features Grid -->
    <section class="max-w-7xl mx-auto px-6 py-24">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-12 text-center">
        <div class="flex flex-col items-center">
          <div class="w-16 h-16 rounded-full bg-[#fdf2ef] text-[#ff8a8a] flex items-center justify-center mb-6">
            <i class="fas fa-leaf text-2xl"></i>
          </div>
          <h3 class="font-bold text-gray-900 text-lg mb-4">No Artificial Fragrances</h3>
          <p class="text-gray-500 text-sm leading-relaxed px-4">
            Our products are 100% naturally derived, ensuring no harsh artificial smells or chemicals.
          </p>
        </div>
        <div class="flex flex-col items-center">
          <div class="w-16 h-16 rounded-full bg-[#fdf2ef] text-[#ff8a8a] flex items-center justify-center mb-6">
            <i class="fas fa-vial text-2xl"></i>
          </div>
          <h3 class="font-bold text-gray-900 text-lg mb-4">No Harsh Chemicals</h3>
          <p class="text-gray-500 text-sm leading-relaxed px-4">
            Formulated without parabens, sulfates, or phthalates. Just clean, effective ingredients.
          </p>
        </div>
        <div class="flex flex-col items-center">
          <div class="w-16 h-16 rounded-full bg-[#fdf2ef] text-[#ff8a8a] flex items-center justify-center mb-6">
            <i class="fas fa-tint text-2xl"></i>
          </div>
          <h3 class="font-bold text-gray-900 text-lg mb-4">Deep Hydration</h3>
          <p class="text-gray-500 text-sm leading-relaxed px-4">
            Infused with natural botanical extracts to keep your skin dewy, glowing, and refreshed.
          </p>
        </div>
      </div>
    </section>

    <!-- Brand Story Section -->
    <section class="bg-[#fdf2ef] py-32 relative overflow-hidden">
      <!-- Decorative Leaves -->
      <i class="fas fa-leaf text-[200px] text-white opacity-20 absolute -left-20 top-10 transform -rotate-45"></i>
      <i class="fas fa-leaf text-[200px] text-white opacity-20 absolute -right-20 bottom-10 transform rotate-[135deg]"></i>
      
      <div class="max-w-4xl mx-auto px-6 text-center relative z-10">
        <p class="text-[10px] font-bold uppercase tracking-[0.2em] text-[#ff8a8a] mb-6">About The Beautifo</p>
        <h2 class="serif-font text-4xl md:text-5xl lg:text-6xl text-gray-900 leading-[1.2] mb-8 max-w-2xl mx-auto">
          Natural organic cosmetics promotes rejuvenation
        </h2>
        <p class="text-gray-600 text-[15px] leading-relaxed mb-16 max-w-3xl mx-auto">
          Founded in 2016, Beautifo brings minimalist, naturally-derived beauty to the modern world. We focus on curating collections that highlight your natural beauty without hiding it behind heavy, unnatural layers. Every product is a testament to our commitment to healthy, glowing skin.
        </p>

        <!-- Video Thumbnail Area -->
        <div class="relative w-full aspect-video rounded-3xl overflow-hidden shadow-2xl group cursor-pointer">
          <img src="https://images.unsplash.com/photo-1556228578-0d85b1a4d571?auto=format&fit=crop&q=80&w=1600" alt="Brand Video" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
          <div class="absolute inset-0 bg-black/20 group-hover:bg-black/30 transition-colors flex items-center justify-center">
            <div class="w-20 h-20 bg-white rounded-full flex items-center justify-center text-[#ff8a8a] shadow-lg transform group-hover:scale-110 transition-transform">
              <i class="fas fa-play text-2xl ml-1"></i>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonial Section -->
    <section class="py-24 bg-white border-b border-gray-100">
      <div class="max-w-3xl mx-auto px-6 text-center">
        <i class="fas fa-quote-right text-4xl text-[#ff8a8a] opacity-30 mb-8"></i>
        <p class="serif-font text-2xl md:text-3xl text-gray-800 italic leading-relaxed mb-10">
          "Beautifo is a very professional team. They are always ready to help and provide the best solutions for our needs. My skin has literally never felt this amazing."
        </p>
        <p class="text-[11px] font-bold uppercase tracking-[0.2em] text-gray-900">
          Alexander <span class="text-gray-400 font-normal ml-2 tracking-normal">— Loyal Customer</span>
        </p>
      </div>
    </section>

    <!-- Promo Banner Section -->
    <section class="relative h-[500px] flex items-center justify-end px-6 lg:px-24">
      <div class="absolute inset-0 z-0">
        <img src="https://images.unsplash.com/photo-1560769629-975ec94e6a86?auto=format&fit=crop&q=80&w=2000" alt="Floral Background" class="w-full h-full object-cover">
        <div class="absolute inset-0 bg-black/10"></div>
      </div>
      
      <div class="relative z-10 bg-white/90 backdrop-blur-sm p-12 md:p-16 rounded-[30px] max-w-lg shadow-xl text-center md:text-left">
        <p class="text-[10px] font-bold uppercase tracking-[0.2em] text-[#ff8a8a] mb-4">Women's Outlet</p>
        <h2 class="serif-font text-4xl md:text-5xl text-gray-900 leading-tight mb-8">
          Further reductions.<br>Up to 70% Off.
        </h2>
        <button class="border-2 border-black text-black hover:bg-black hover:text-white px-8 py-3.5 rounded-full font-bold text-[11px] uppercase tracking-widest transition-colors duration-300">
          Shop Now
        </button>
      </div>
    </section>

  </main>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const slides = [
  "https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&q=80&w=2000",
  "https://images.unsplash.com/photo-1612817288484-6f916006741a?auto=format&fit=crop&q=80&w=2000",
  "https://images.unsplash.com/photo-1556228578-0d85b1a4d571?auto=format&fit=crop&q=80&w=2000"
]

const currentSlide = ref(0)
let slideInterval

onMounted(() => {
  slideInterval = setInterval(() => {
    currentSlide.value = (currentSlide.value + 1) % slides.length
  }, 4000)
})

onUnmounted(() => {
  if (slideInterval) clearInterval(slideInterval)
})
</script>

<style scoped>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 1.5s ease-in-out;
}
.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
</style>
