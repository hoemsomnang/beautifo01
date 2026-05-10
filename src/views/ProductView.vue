<template>
  <main class="max-w-7xl mx-auto px-4 lg:px-6 py-12">
    
    <!-- Top Section: Product Details -->
    <div class="flex flex-col lg:flex-row gap-12 mb-20">
      
      <!-- Left: Product Image -->
      <div class="lg:w-1/2">
        <div class="bg-[#f8f5f6] rounded-2xl relative aspect-square flex items-center justify-center p-12">
          <button class="absolute top-6 right-6 w-8 h-8 bg-white rounded-full flex items-center justify-center shadow-sm text-gray-500 hover:text-black transition-colors" aria-label="Zoom image">
            <i class="fas fa-search text-xs"></i>
          </button>
          <!-- Using a placeholder similar to the image -->
          <img src="https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-10.jpg" alt="Serveware & Serving Dish Sets" class="w-full h-full object-contain mix-blend-multiply drop-shadow-xl animate-float">
        </div>
      </div>

      <!-- Right: Product Info -->
      <div class="lg:w-1/2 flex flex-col justify-center">
        <div>
          <span class="bg-[#8cc63f] text-white text-[9px] font-bold px-2 py-0.5 rounded-sm uppercase tracking-wider">Sale</span>
        </div>
        
        <h1 class="text-3xl lg:text-4xl font-bold text-gray-900 mt-4 mb-2 tracking-tight">Serveware & Serving Dish Sets 75ml</h1>
        
        <div class="flex items-center gap-2 mb-6">
          <div class="flex text-[10px] space-x-0.5 text-pink-accent">
            <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star-half-alt"></i>
          </div>
          <span class="text-xs text-gray-400">(2 customer reviews)</span>
        </div>

        <div class="flex items-baseline gap-3 mb-6">
          <span class="text-2xl font-bold text-gray-900">£72.00</span>
          <span class="text-sm text-gray-400 line-through">£120.28</span>
        </div>

        <div class="w-full h-px bg-gray-200 mb-6"></div>

        <p class="text-sm text-gray-500 leading-relaxed mb-8">
          An dico accommodare ius, porro mnesarchum pro in. Cetero fierem urbanitas eam id, sed movet noluisse ut. Eu agam malorum nec. Eu has vide putent, dico option nominati no eam. Ea erant impetus consequuntur eos, velit congue vidisse eos ne.
        </p>

        <div class="mb-8">
          <p class="text-xs font-bold text-gray-900 mb-3">Quantity:</p>
          <div class="flex items-center gap-4">
            <div class="flex items-center border border-gray-200 rounded-full overflow-hidden h-11 w-32">
              <button class="w-10 h-full flex items-center justify-center text-gray-500 hover:bg-gray-50 transition-colors" @click="quantity > 1 ? quantity-- : null"><i class="fas fa-minus text-[10px]"></i></button>
              <input type="number" v-model="quantity" class="w-full h-full text-center text-sm font-bold border-none outline-none text-gray-900 appearance-none bg-transparent m-0 p-0" min="1">
              <button class="w-10 h-full flex items-center justify-center text-gray-500 hover:bg-gray-50 transition-colors" @click="quantity++"><i class="fas fa-plus text-[10px]"></i></button>
            </div>
            
            <button class="bg-pink-accent hover:bg-black text-white px-8 py-3.5 rounded-full font-bold text-[11px] uppercase tracking-widest transition-all duration-300 shadow-lg shadow-pink-accent/20 flex items-center gap-2">
              <i class="fas fa-shopping-bag text-xs"></i> Add to cart
            </button>
          </div>
        </div>

        <div class="flex items-center gap-6 mb-8 text-xs text-gray-500 font-medium">
          <button class="hover:text-pink-accent transition-colors flex items-center gap-2"><i class="far fa-heart"></i> Add to wishlist</button>
          <button class="hover:text-pink-accent transition-colors flex items-center gap-2"><i class="fas fa-arrows-rotate"></i> Compare</button>
        </div>

        <div class="w-full h-px bg-gray-200 mb-6"></div>

        <div class="space-y-3 text-xs text-gray-500">
          <p><span class="font-bold text-gray-900 w-24 inline-block">SKU:</span> N/A-646</p>
          <p><span class="font-bold text-gray-900 w-24 inline-block">Categories:</span> <a href="#" class="hover:text-pink-accent transition-colors">Applicators</a>, <a href="#" class="hover:text-pink-accent transition-colors">Face Masks</a></p>
          <p><span class="font-bold text-gray-900 w-24 inline-block">Tags:</span> <a href="#" class="hover:text-pink-accent transition-colors">Make Up</a>, <a href="#" class="hover:text-pink-accent transition-colors">Organic</a></p>
          <div class="flex items-center gap-3">
            <span class="font-bold text-gray-900 w-24 inline-block">Share:</span>
            <div class="flex items-center gap-3 text-gray-400">
              <a href="#" class="hover:text-pink-accent transition-colors"><i class="fab fa-facebook-f"></i></a>
              <a href="#" class="hover:text-pink-accent transition-colors"><i class="fab fa-twitter"></i></a>
              <a href="#" class="hover:text-pink-accent transition-colors"><i class="fab fa-pinterest-p"></i></a>
              <a href="#" class="hover:text-pink-accent transition-colors"><i class="fab fa-linkedin-in"></i></a>
            </div>
          </div>
        </div>

      </div>
    </div>

    <!-- Middle Section: Tabs -->
    <div class="mb-24">
      <div class="flex justify-center gap-8 mb-6 text-sm font-bold text-gray-500 border-b border-gray-100">
        <button class="pb-4 border-b-2 border-pink-accent text-pink-accent">Description</button>
        <button class="pb-4 border-b-2 border-transparent hover:text-gray-900 transition-colors">Additional information</button>
        <button class="pb-4 border-b-2 border-transparent hover:text-gray-900 transition-colors">Reviews (5)</button>
      </div>

      <div class="border border-gray-100 rounded-[20px] p-8 lg:p-12 shadow-sm bg-white">
        <p class="text-sm text-gray-500 leading-relaxed mb-8">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </p>

        <h4 class="font-bold text-gray-900 mb-4 text-sm">Product Features</h4>
        <ul class="space-y-4 text-sm text-gray-500">
          <li class="flex items-start gap-3">
            <i class="far fa-check-circle text-pink-accent mt-0.5"></i>
            <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</span>
          </li>
          <li class="flex items-start gap-3">
            <i class="far fa-check-circle text-pink-accent mt-0.5"></i>
            <span>Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</span>
          </li>
          <li class="flex items-start gap-3">
            <i class="far fa-check-circle text-pink-accent mt-0.5"></i>
            <span>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</span>
          </li>
          <li class="flex items-start gap-3">
            <i class="far fa-check-circle text-pink-accent mt-0.5"></i>
            <span>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</span>
          </li>
        </ul>

        <p class="text-sm text-gray-500 leading-relaxed mt-8">
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.
        </p>
      </div>
    </div>

    <!-- Bottom Section: Related Products -->
    <section>
      <h2 class="text-2xl font-bold text-gray-900 mb-10">Related products</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-x-6 gap-y-12">
        <ProductCard v-for="p in relatedProducts" :key="p.name" :product="p" />
      </div>
    </section>

  </main>
</template>

<script setup>
import { ref } from 'vue'
import ProductCard from '../components/ProductCard.vue'

const quantity = ref(1)

const relatedProducts = [
  { name: "Buy Oriflame Milk & Honey Gold Shampoo", price: "126.00", oldPrice: "105.00", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-02.jpg" },
  { name: "Benefits of Skincare for Oily Skin", price: "116.00", oldPrice: "105.00", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-06.jpg" },
  { name: "Body Partner Stretch Mark Cream", price: "116.00", oldPrice: "167.53", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-14.jpg" },
  { name: "Daily Moisturizing Lotion for Dry Skin", price: "133.00", oldPrice: "191.65", image: "https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-13.jpg" }
]
</script>

<style scoped>
/* To hide the number input arrows */
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  -webkit-appearance: none;
  margin: 0;
}
input[type="number"] {
  -moz-appearance: textfield;
}
</style>
