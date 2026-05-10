<template>
  <section class="text-center mb-16">
    <h2 class="text-3xl font-bold text-gray-900 mb-10">Featured Products</h2>
    <div class="flex flex-wrap justify-center gap-6 text-[10px] font-bold tracking-[0.2em] uppercase text-gray-400 mb-12">
      <button class="bg-pink-accent text-white px-8 py-2.5 rounded-full shadow-lg shadow-pink-100">All</button>
      <button class="hover:text-pink-accent px-2 transition-colors">For face</button>
      <button class="hover:text-pink-accent px-2 transition-colors">For body</button>
      <button class="hover:text-pink-accent px-2 transition-colors">For hair</button>
      <button class="hover:text-pink-accent px-2 transition-colors">Accessories</button>
    </div>

    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-x-6 gap-y-12">
      <ProductCard v-for="p in featuredProducts" :key="p.name" :product="p" />
    </div>
  </section>
</template>

<script setup>
import ProductCard from './ProductCard.vue'
const featuredProducts = [
  { name: "florence by mills Mind Glowing Peel", price: "112.00", oldPrice: "160.93", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-02.jpg" },
  { name: "Serveware & Serving Dish Sets 75ml", price: "72.00", oldPrice: "120.28", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-10.jpg" },
  { name: "SOS Hydra Refreshing Hydration Mask", price: "109.00", oldPrice: "156.16", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-12.jpg" },
  { name: "Rational Household Labor Supply – JSTOR", price: "118.00", oldPrice: "148.33", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-14.jpg" },
  { name: "Kiko Milano Smart Hydrating Foundation", price: "96.00", oldPrice: "121.54", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-13.jpg" },
  { name: "Kerastase Discipline Bain Fluidealiste", price: "116.00", oldPrice: "167.53", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-15-1.jpg" },
  { name: "Illuminating Serum Primer — By Mills", price: "90.00", oldPrice: "113.19", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-11.jpg" },
  { name: "Hydrating Cream Mask 75ml tube", price: "84.00", oldPrice: "140.92", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-06.jpg" }
];
</script>
