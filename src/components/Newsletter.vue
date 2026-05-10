<template>
  <section class="mb-24">
    <!-- Newsletter Banner -->
    <div class="relative overflow-hidden rounded-[40px] bg-gradient-to-r from-[#fce4ec] via-[#fde2e2] to-[#fce4ec] shadow-premium min-h-[350px] flex flex-col items-center justify-center px-6 text-center border border-white/80">
      <!-- Floral Decorative Elements -->
      <div class="absolute inset-0 pointer-events-none opacity-40">
        <svg class="absolute -left-10 top-0 w-64 h-64 text-pink-300" viewBox="0 0 100 100" fill="currentColor">
          <path d="M50 0 C60 30 90 40 90 50 C90 60 60 70 50 100 C40 70 10 60 10 50 C10 40 40 30 50 0" />
        </svg>
        <svg class="absolute -right-20 bottom-0 w-80 h-80 text-pink-200" viewBox="0 0 100 100" fill="currentColor">
          <path d="M50 0 C70 20 100 50 50 100 C0 50 30 20 50 0" />
        </svg>
      </div>

      <div class="relative z-10 max-w-2xl">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Sign up now & get 10% off</h2>
        <p class="text-gray-500 text-sm md:text-base mb-10 leading-relaxed">
          Subscribe to our emails (they're super fun, promise) and get 15% off your first online order
        </p>
        
        <div class="flex flex-col sm:flex-row gap-4 w-full max-w-xl mx-auto">
          <input type="email" placeholder="Your email address" 
                 class="flex-grow px-8 py-4 rounded-full border-none focus:ring-2 focus:ring-pink-300 outline-none text-sm shadow-sm"
                 aria-label="Email subscription">
          <button class="bg-[#ff8a8a] text-white font-bold text-[11px] uppercase tracking-widest px-10 py-4 rounded-full hover:bg-black transition-all duration-300 shadow-lg">
            Subscribe <i class="fas fa-angles-right ml-2 text-[8px]"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- Blog Section -->
    <div class="mt-24">
      <div class="text-center mb-16">
        <h2 class="text-4xl font-bold text-gray-900 mb-4">From The Blog</h2>
        <p class="text-gray-500 text-sm max-w-lg mx-auto leading-relaxed px-4">
          Get all latest skincare essentials news, tips and tricks to nurture your skin glowy, dewy best before you even think makeup
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
        <!-- Blog Post 1 -->
        <div class="group cursor-pointer hover:shadow-premium-hover transition-all duration-500 rounded-[35px] p-2 bg-white border border-gray-50">
          <div class="overflow-hidden rounded-[30px] mb-6 aspect-[1.4/1] bg-gray-50">
            <img src="https://images.unsplash.com/photo-1556228720-195a672e8a03?auto=format&fit=crop&q=80&w=800" 
                 alt="Luxury beauty cosmetic cream" 
                 class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
          </div>
          <h3 class="text-lg font-bold text-gray-900 mb-3 leading-tight group-hover:text-pink-accent transition-colors">
            Tips & procedure to apply luxury beauty cosmetic cream
          </h3>
          <p class="text-[10px] font-bold text-gray-400 uppercase tracking-[0.2em]">April 2, 2021</p>
        </div>

        <!-- Blog Post 2 -->
        <div class="group cursor-pointer hover:shadow-premium-hover transition-all duration-500 rounded-[35px] p-2 bg-white border border-gray-50">
          <div class="overflow-hidden rounded-[30px] mb-6 aspect-[1.4/1] bg-gray-50">
            <img src="https://images.unsplash.com/photo-1612817288484-6f916006741a?auto=format&fit=crop&q=80&w=800" 
                 alt="Makeup brushes" 
                 class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
          </div>
          <h3 class="text-lg font-bold text-gray-900 mb-3 leading-tight group-hover:text-pink-accent transition-colors">
            The best part about makeup is brush and its types
          </h3>
          <p class="text-[10px] font-bold text-gray-400 uppercase tracking-[0.2em]">April 2, 2021</p>
        </div>

        <!-- Blog Post 3 -->
        <div class="group cursor-pointer hover:shadow-premium-hover transition-all duration-500 rounded-[35px] p-2 bg-white border border-gray-50">
          <div class="overflow-hidden rounded-[30px] mb-6 aspect-[1.4/1] bg-gray-50">
            <img src="https://images.unsplash.com/photo-1556228720-195a672e8a03?auto=format&fit=crop&q=80&w=800" 
                 alt="Lightweight makeup" 
                 class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
          </div>
          <h3 class="text-lg font-bold text-gray-900 mb-3 leading-tight group-hover:text-pink-accent transition-colors">
            Lightweight makeup to enhance your natural beauty
          </h3>
          <p class="text-[10px] font-bold text-gray-400 uppercase tracking-[0.2em]">April 2, 2021</p>
        </div>
      </div>
    </div>

    <!-- Partner Logos -->
    <div class="mt-20 border-t border-gray-100 pt-16">
      <div class="flex flex-wrap justify-between items-center gap-10 opacity-60 hover:opacity-100 transition-opacity duration-500 px-4">
        <div class="flex flex-col items-center group">
          <i class="fas fa-spa text-3xl mb-2 text-gray-400 group-hover:text-pink-accent"></i>
          <span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-500">Spa & Beauty</span>
        </div>
        <div class="flex flex-col items-center group">
          <i class="fas fa-leaf text-3xl mb-2 text-gray-400 group-hover:text-pink-accent"></i>
          <span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-500">Pure Beauty</span>
        </div>
        <div class="flex flex-col items-center group">
          <span class="serif-font italic text-2xl mb-1 text-gray-500 group-hover:text-pink-accent">Louis Janne</span>
          <span class="text-[8px] uppercase tracking-[0.3em] text-gray-400">Photography</span>
        </div>
        <div class="flex flex-col items-center group">
          <i class="fas fa-gem text-3xl mb-2 text-gray-400 group-hover:text-pink-accent"></i>
          <span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-500">Beauty Luxury</span>
        </div>
        <div class="flex flex-col items-center group">
          <i class="fas fa-wind text-3xl mb-2 text-gray-400 group-hover:text-pink-accent"></i>
          <span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-500">Nature Rituals</span>
        </div>
      </div>
    </div>
  </section>
</template>
