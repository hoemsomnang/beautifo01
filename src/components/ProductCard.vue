<template>
  <div class="product-card group flex flex-col cursor-pointer" @click="$router.push('/product')">
    <div class="bg-[#f8f8f8] relative aspect-square w-full rounded-2xl flex items-center justify-center overflow-hidden mb-5">
      <span class="absolute top-4 left-4 bg-[#8cc63f] text-white text-[9px] font-bold px-2 py-0.5 rounded-sm uppercase z-20">In Stock</span>
      <span class="absolute top-4 right-4 bg-[#ef4444] text-white text-[9px] font-bold px-2 py-0.5 rounded-sm uppercase z-20">Sale</span>
      
      <img :src="product.image || 'https://placehold.co/400x400/f8f8f8/999?text=Product'" 
           :alt="product.name" 
           @error="$event.target.src='https://placehold.co/400x400/f8f8f8/999?text=Product'"
           class="w-[85%] h-[85%] object-contain mix-blend-multiply transition-transform duration-500 ease-out group-hover:scale-105 p-4 z-10">
      
      <!-- Right Side Hover Actions (Vertical Stack) -->
      <div class="absolute top-4 right-4 flex flex-col space-y-2 transition-all duration-300 transform translate-x-8 opacity-0 group-hover:translate-x-0 group-hover:opacity-100 z-30">
        <button class="w-9 h-9 bg-white hover:bg-[#ff8a8a] text-gray-800 hover:text-white rounded-full flex items-center justify-center text-xs shadow-md transition-colors duration-300" aria-label="Add to Wishlist" @click.stop><i class="far fa-heart"></i></button>
        <button class="w-9 h-9 bg-white hover:bg-[#ff8a8a] text-gray-800 hover:text-white rounded-full flex items-center justify-center text-xs shadow-md transition-colors duration-300" aria-label="Compare" @click.stop><i class="fas fa-arrows-rotate"></i></button>
        <button class="w-9 h-9 bg-white hover:bg-[#ff8a8a] text-gray-800 hover:text-white rounded-full flex items-center justify-center text-xs shadow-md transition-colors duration-300" aria-label="Quick View" @click.stop><i class="far fa-eye"></i></button>
      </div>

      <!-- Bottom Hover Action (Add to Cart) -->
      <div class="absolute bottom-0 left-0 right-0 transition-all duration-300 transform translate-y-full group-hover:translate-y-0 z-30">
        <button class="w-full bg-[#111] hover:bg-[#ff8a8a] text-white py-3.5 text-[11px] font-bold uppercase tracking-widest transition-colors duration-300" @click.stop>
          Add to Cart
        </button>
      </div>
    </div>

    <!-- Product Details -->
    <div class="text-center px-2">
      <h3 class="text-[14px] text-[#222] mb-1 leading-tight h-10 overflow-hidden group-hover:text-[#ff8a8a] transition-colors">{{ product.name }}</h3>
      
      <div class="rating-stars mb-2 flex justify-center text-[9px] space-x-0.5 text-[#ff8a8a]">
        <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star text-gray-200"></i>
      </div>

      <div class="flex justify-center items-center space-x-2 text-[14px]">
        <span class="font-bold text-[#222]">£{{ product.price }}</span>
        <span class="text-gray-400 line-through text-[12px]">£{{ product.oldPrice }}</span>
      </div>
    </div>
  </div>
</template>

<script setup>
defineProps({
  product: {
    type: Object,
    required: true
  }
})
</script>
