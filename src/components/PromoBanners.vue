<template>
  <section class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-16">
    <div class="bg-gradient-to-br from-[#d1e8e4] to-[#e8f6f4] shadow-sm border border-white/60 rounded-[40px] overflow-hidden relative group h-[320px] flex items-center p-12 transition-all duration-500 hover:shadow-premium-hover">
      <div class="z-10 relative">
        <p class="text-pink-accent text-[11px] font-bold uppercase tracking-[0.2em] mb-3">Up to 30% Off</p>
        <h3 class="text-3xl font-semibold text-gray-800 mb-8 leading-tight">Natural Beauty<br>Collection</h3>
        <a href="#" class="text-[11px] font-bold uppercase tracking-widest border-b-2 border-black pb-1 hover:text-pink-accent hover:border-pink-accent transition-all inline-flex items-center">
          SHOP NOW <i class="fas fa-angles-right ml-2 text-[8px]"></i>
        </a>
      </div>
      <img src="https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/rev_home1_2.png" 
           @error="$event.target.src='https://images.unsplash.com/photo-1556228720-195a672e8a03?auto=format&fit=crop&q=80&w=600'"
           alt="Natural Beauty Collection" 
           class="absolute right-0 bottom-0 h-[110%] w-auto object-contain p-4 translate-x-4 translate-y-4 group-hover:scale-105 group-hover:translate-x-0 transition-all duration-700 ease-out z-0">
    </div>

    <div class="bg-gradient-to-br from-[#e9ebf3] to-[#f4f5f9] shadow-sm border border-white/60 rounded-[40px] overflow-hidden relative group h-[320px] flex items-center p-12 transition-all duration-500 hover:shadow-premium-hover">
      <div class="z-10 relative">
        <p class="text-gray-500 text-[11px] font-medium uppercase tracking-widest mb-1">Look Gorgeous</p>
        <h3 class="text-4xl font-bold text-gray-800 mb-2">Hair Mask</h3>
        <p class="text-pink-accent text-[10px] font-bold uppercase tracking-[0.25em] mb-10">Total Hair Repair</p>
        <a href="#" class="text-[11px] font-bold uppercase tracking-widest border-b-2 border-black pb-1 hover:text-pink-accent hover:border-pink-accent transition-all inline-flex items-center">
          SHOP NOW <i class="fas fa-angles-right ml-2 text-[8px]"></i>
        </a>
      </div>
      <img src="https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/rev_home1_2.png" 
           @error="$event.target.src='https://images.unsplash.com/photo-1596462502278-27bfad450216?auto=format&fit=crop&q=80&w=600'"
           alt="Hair Mask Treatment" 
           class="absolute right-0 top-0 h-full w-auto object-cover group-hover:scale-105 transition-transform duration-1000 ease-in-out">
    </div>
  </section>
</template>
