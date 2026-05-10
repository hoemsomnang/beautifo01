<template>
  <section class="mb-24">
    <div class="text-center mb-12">
      <p class="text-gray-500 text-sm tracking-wide">
        Get hands on with our recipe ideas. 
        <a href="#" class="text-pink-accent font-bold border-b border-pink-accent pb-0.5 hover:text-gray-900 hover:border-gray-900 transition-all ml-1">
          Shop All Products <i class="fas fa-angles-right text-[8px] ml-1"></i>
        </a>
      </p>
    </div>
    
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 auto-rows-fr">
      <!-- Left Tall Banner -->
      <div class="md:col-span-1 md:row-span-2 relative group overflow-hidden rounded-[32px] bg-gradient-to-br from-[#e3ded4] to-[#f4f2ee] shadow-sm border border-white/60 min-h-[550px] p-10 flex flex-col justify-start hover:shadow-premium-hover transition-shadow duration-500">
        <div class="z-10">
          <p class="text-pink-accent text-[11px] font-bold uppercase tracking-[0.2em] mb-3">Up to 50% Off</p>
          <h3 class="text-4xl font-medium text-gray-800 mb-10 leading-tight">Super Natural<br>Beauty</h3>
          <a href="#" class="text-[11px] font-bold uppercase tracking-widest border-b-2 border-black pb-1 w-fit group-hover:text-pink-accent group-hover:border-pink-accent transition-all">SHOP NOW <i class="fas fa-angles-right ml-1 text-[8px]"></i></a>
        </div>
        <img src="https://images.unsplash.com/photo-1620916566398-39f1143ab7be?auto=format&fit=crop&q=80&w=800" 
             alt="Natural Beauty" 
             class="absolute bottom-0 right-0 w-full h-2/3 object-contain pointer-events-none transform group-hover:scale-105 transition-transform duration-700">
      </div>

      <!-- Top Center Banner -->
      <div class="md:col-span-1 relative group overflow-hidden rounded-[32px] bg-gradient-to-br from-[#f7d6d6] to-[#fceeee] shadow-sm border border-white/60 h-[263px] p-10 flex flex-col justify-center hover:shadow-premium-hover transition-shadow duration-500">
        <div class="z-10">
          <p class="text-gray-800 font-bold text-2xl mb-1">10% OFF</p>
          <h3 class="text-xl font-light text-gray-700 mb-6">Body Butter</h3>
          <a href="#" class="text-[11px] font-bold uppercase tracking-widest border-b-2 border-black pb-1 group-hover:text-pink-accent group-hover:border-pink-accent transition-all">SHOP NOW <i class="fas fa-angles-right ml-1 text-[8px]"></i></a>
        </div>
        <img src="https://images.unsplash.com/photo-1620916566398-39f1143ab7be?auto=format&fit=crop&q=80&w=600" 
             alt="Body Butter" 
             class="absolute right-0 top-0 h-full w-2/3 object-contain p-4 transform group-hover:scale-110 transition-transform duration-500">
      </div>

      <!-- Top Right Banner -->
      <div class="md:col-span-1 relative group overflow-hidden rounded-[32px] bg-gradient-to-br from-[#ececec] to-[#f9f9f9] shadow-sm border border-white/60 h-[263px] p-10 flex flex-col justify-center hover:shadow-premium-hover transition-shadow duration-500">
        <div class="z-10">
          <p class="text-pink-accent text-[10px] font-bold tracking-widest mb-1 uppercase">Skin 2.0</p>
          <h3 class="text-2xl font-semibold text-gray-800 mb-6">Health<br>& Beauty</h3>
          <a href="#" class="text-[11px] font-bold uppercase tracking-widest border-b-2 border-black pb-1 group-hover:text-pink-accent group-hover:border-pink-accent transition-all">SHOP NOW <i class="fas fa-angles-right ml-1 text-[8px]"></i></a>
        </div>
        <img src="https://images.unsplash.com/photo-1620916566398-39f1143ab7be?auto=format&fit=crop&q=80&w=600" 
             alt="Health Beauty" 
             class="absolute right-0 top-0 h-full w-2/3 object-contain p-4 transform group-hover:scale-110 transition-transform duration-500">
      </div>

      <!-- Bottom Wide Banner -->
      <div class="md:col-span-2 relative group overflow-hidden rounded-[32px] bg-gradient-to-r from-[#cbd5e1] to-[#e2e8f0] shadow-sm border border-white/60 min-h-[263px] flex items-center px-12 hover:shadow-premium-hover transition-shadow duration-500">
        <div class="z-10">
          <h3 class="text-4xl font-bold text-white mb-2 leading-tight">Beauty &<br>Spa Treatments</h3>
          <p class="text-yellow-200 text-[10px] font-bold uppercase tracking-[0.2em] mb-8">Skin - Hair - Body</p>
          <a href="#" class="text-[11px] font-bold text-white uppercase tracking-widest border-b-2 border-white pb-1 group-hover:text-yellow-200 group-hover:border-yellow-200 transition-all">SHOP NOW <i class="fas fa-angles-right ml-1 text-[8px]"></i></a>
        </div>
        <img src="https://images.unsplash.com/photo-1544161515-4ab6ce6db874?auto=format&fit=crop&q=80&w=1200" 
             alt="Spa Treatments" 
             class="absolute inset-0 w-full h-full object-cover transform group-hover:scale-105 transition-transform duration-700 opacity-90">
      </div>
    </div>
  </section>
</template>
