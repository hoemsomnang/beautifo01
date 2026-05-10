<template>
  <header class="bg-white sticky top-0 z-50 border-b border-gray-50 transition-all duration-300">
    <nav class="max-w-7xl mx-auto px-6 h-20 grid grid-cols-3 items-center">
      
      <!-- Left: Menu -->
      <div class="hidden lg:flex space-x-6 text-[11px] font-bold uppercase tracking-widest text-gray-800">
        <router-link to="/" class="hover:text-[#ff8a8a] transition-colors" exact-active-class="text-[#ff8a8a]">Home</router-link>
        <router-link to="/shop" class="hover:text-[#ff8a8a] transition-colors" active-class="text-[#ff8a8a]">Shop</router-link>
        <router-link to="/about" class="hover:text-[#ff8a8a] transition-colors" active-class="text-[#ff8a8a]">About us</router-link>
        <router-link to="/blog" class="hover:text-[#ff8a8a] transition-colors" active-class="text-[#ff8a8a]">Blog</router-link>
        <router-link to="/contact" class="hover:text-[#ff8a8a] transition-colors" active-class="text-[#ff8a8a]">Contact us</router-link>
      </div>

      <!-- Mobile Menu Button -->
      <div class="lg:hidden flex items-center">
        <button class="text-gray-900" aria-label="Menu">
          <i class="fas fa-bars text-xl"></i>
        </button>
      </div>

      <!-- Center: Logo -->
      <div class="flex justify-center items-center">
        <div class="logo-font text-3xl tracking-widest relative cursor-pointer">
          BEA<span class="text-[#ff8a8a] relative inline-block mx-0.5">
            U
            <svg class="absolute -top-1 -left-1 w-6 h-6 opacity-60" viewBox="0 0 24 24" fill="currentColor">
              <path d="M12,2C12,2 14,8 20,10C14,12 12,18 12,18C12,18 10,12 4,10C10,8 12,2 12,2Z" />
            </svg>
          </span>TIFO
        </div>
      </div>

      <!-- Right: Icons -->
      <div class="flex items-center justify-end space-x-5 text-gray-800 text-[13px]">
        <button class="hover:text-[#ff8a8a] transition-colors" aria-label="Search"><i class="fas fa-search"></i></button>
        <button class="hover:text-[#ff8a8a] transition-colors" aria-label="Account"><i class="far fa-user"></i></button>
        <button class="hover:text-[#ff8a8a] transition-colors relative" aria-label="Wishlist">
          <i class="far fa-heart"></i>
          <span class="absolute -top-2 -right-2 bg-red-500 text-white text-[9px] font-bold w-4 h-4 rounded-full flex items-center justify-center">0</span>
        </button>
        <button class="hover:text-[#ff8a8a] transition-colors relative" aria-label="Cart">
          <i class="fas fa-shopping-bag"></i>
          <span class="absolute -top-2 -right-2 bg-red-500 text-white text-[9px] font-bold w-4 h-4 rounded-full flex items-center justify-center">0</span>
        </button>
      </div>
    </nav>
  </header>
</template>
