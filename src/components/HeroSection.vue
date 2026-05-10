<template>
  <section class="mt-4 mb-8">
    <div class="bg-[#e8dfd5] rounded-[40px] overflow-hidden relative flex flex-col lg:flex-row items-center min-h-[600px]">
      
      <!-- Left Content: Image -->
      <div class="lg:w-1/2 h-[400px] lg:h-[600px] relative order-2 lg:order-1 hero-zoom flex justify-center items-end">
        <img src="https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/slider-01.png" alt="Beautifo Model" class="hero-img object-cover h-[90%] w-auto z-10 drop-shadow-xl" onerror="this.src='https://images.unsplash.com/photo-1612817288484-6f916006741a?auto=format&fit=crop&q=80&w=800'">
      </div>

      <!-- Right Content: Typography and CTA -->
      <div class="lg:w-1/2 p-12 lg:p-24 z-20 text-center lg:text-left order-1 lg:order-2">
        <h2 class="serif-font text-5xl md:text-7xl lg:text-[80px] leading-[1.1] text-[#222] mb-6">
          <span class="block">Discover</span>
          <span class="block text-[#ff8a8a] italic font-medium">The Secrets Of</span>
          <span class="block">Beautifo</span>
        </h2>
        <p class="text-gray-500 mb-10 max-w-md mx-auto lg:mx-0 text-sm leading-relaxed">
          Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur.
        </p>
        <button class="bg-[#111] text-white px-10 py-4 rounded-full font-bold text-[11px] uppercase tracking-[0.2em] hover:bg-[#ff8a8a] transition-colors duration-300 shadow-xl inline-flex items-center gap-2">
          Shop Now <i class="fas fa-angle-double-right text-[10px]"></i>
        </button>
      </div>
      
    </div>
  </section>
</template>
