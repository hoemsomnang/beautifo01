<template>
  <footer class="bg-[#f8f4f2] pt-20 border-t border-gray-100">
    <div class="max-w-7xl mx-auto px-6">
      
      <!-- Trust Badges Section -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-20 text-center">
        <!-- Samples -->
        <div class="flex flex-col items-center px-4">
          <div class="text-[#ff8a8a] mb-4">
            <svg class="w-10 h-10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
              <path d="M9 3h6M10 3v3m4-3v3M8 6h8l1 15H7L8 6zM12 11v6M9 14h6" />
            </svg>
          </div>
          <h4 class="font-bold text-[#222] text-sm mb-1 uppercase tracking-widest">Free Deluxe Samples</h4>
          <p class="text-gray-500 text-xs italic">On orders over $60</p>
        </div>
        
        <!-- Reward Points -->
        <div class="flex flex-col items-center px-4 border-t md:border-t-0 md:border-l border-gray-200 pt-8 md:pt-0">
          <div class="text-[#ff8a8a] mb-4">
            <svg class="w-10 h-10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
              <rect x="3" y="6" width="18" height="12" rx="2" />
              <path d="M3 10h18M7 15h.01M11 15h.01" />
            </svg>
          </div>
          <h4 class="font-bold text-[#222] text-sm mb-1 uppercase tracking-widest">Earn Reward Points</h4>
          <p class="text-gray-500 text-xs italic">With our loyalty programme</p>
        </div>

        <!-- Delivery -->
        <div class="flex flex-col items-center px-4 border-t md:border-t-0 md:border-l border-gray-200 pt-8 md:pt-0">
          <div class="text-[#ff8a8a] mb-4">
            <svg class="w-10 h-10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
              <rect x="1" y="3" width="15" height="13" />
              <polygon points="16 8 20 8 23 11 23 16 16 16 16 8" />
              <circle cx="5.5" cy="18.5" r="2.5" />
              <circle cx="18.5" cy="18.5" r="2.5" />
            </svg>
          </div>
          <h4 class="font-bold text-[#222] text-sm mb-1 uppercase tracking-widest">Free Standard Delivery</h4>
          <p class="text-gray-500 text-xs italic">on UK orders over $30</p>
        </div>
      </div>

      <div class="border-t border-gray-200 pt-16 grid grid-cols-1 md:grid-cols-12 gap-10 pb-16">
        <!-- Brand Info -->
        <div class="md:col-span-12 lg:col-span-4 pr-0 lg:pr-12">
          <div class="logo-font text-3xl text-[#222] flex items-center mb-6">
            BEA<span class="text-[#ff8a8a] relative inline-block mx-0.5">
              U
              <svg class="absolute -top-1 -left-1 w-6 h-6 opacity-60" viewBox="0 0 24 24" fill="currentColor">
                <path d="M12,2C12,2 14,8 20,10C14,12 12,18 12,18C12,18 10,12 4,10C10,8 12,2 12,2Z" />
              </svg>
            </span>TIFO
          </div>
          <p class="text-gray-500 text-[13px] leading-relaxed mb-6 font-medium">
            Beautiful — a popular online beauty store that sells all cosmetics products in order to nature your skin for your own way.
          </p>
          <div class="flex flex-col space-y-2">
            <a href="tel:18008866990" class="text-[#222] text-[13px] font-bold hover:text-[#ff8a8a] transition-colors">
              (1800)-88-66-990
            </a>
            <a href="mailto:contact@beautifo.com" class="text-gray-500 text-[13px] hover:text-[#ff8a8a] transition-colors">
              contact@example.com
            </a>
          </div>
        </div>

        <!-- Nav Columns -->
        <div class="md:col-span-3 lg:col-span-2">
          <h4 class="font-bold text-[#222] text-sm mb-6">About us</h4>
          <ul class="text-[13px] text-gray-500 space-y-3">
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Story</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Products</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Blog</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Giving Back</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Partnerships</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Careers</a></li>
          </ul>
        </div>

        <div class="md:col-span-3 lg:col-span-2">
          <h4 class="font-bold text-[#222] text-sm mb-6">Support</h4>
          <ul class="text-[13px] text-gray-500 space-y-3">
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Shipping Info</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Returns & Exchanges</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Help & FAQ</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Reviews</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Quiz</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Store Locator</a></li>
          </ul>
        </div>

        <div class="md:col-span-3 lg:col-span-2">
          <h4 class="font-bold text-[#222] text-sm mb-6">Services</h4>
          <ul class="text-[13px] text-gray-500 space-y-3">
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Contact us</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Delivery</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Returns</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">My account</a></li>
            <li><a href="#" class="hover:text-[#ff8a8a] transition-colors">Rewards</a></li>
          </ul>
        </div>

        <div class="md:col-span-3 lg:col-span-2">
          <h4 class="font-bold text-[#222] text-sm mb-6">Socials</h4>
          <ul class="text-[13px] text-gray-500 space-y-3">
            <li class="flex items-center group">
              <span class="w-7 h-7 rounded-full bg-white text-[#ff8a8a] flex items-center justify-center mr-3 group-hover:bg-[#ff8a8a] group-hover:text-white transition-colors shadow-sm"><i class="fab fa-facebook-f text-[10px]"></i></span>
              <a href="#" class="hover:text-[#ff8a8a] transition-colors">Facebook</a>
            </li>
            <li class="flex items-center group">
              <span class="w-7 h-7 rounded-full bg-white text-[#ff8a8a] flex items-center justify-center mr-3 group-hover:bg-[#ff8a8a] group-hover:text-white transition-colors shadow-sm"><i class="fab fa-twitter text-[10px]"></i></span>
              <a href="#" class="hover:text-[#ff8a8a] transition-colors">Twitter</a>
            </li>
            <li class="flex items-center group">
              <span class="w-7 h-7 rounded-full bg-white text-[#ff8a8a] flex items-center justify-center mr-3 group-hover:bg-[#ff8a8a] group-hover:text-white transition-colors shadow-sm"><i class="fab fa-linkedin-in text-[10px]"></i></span>
              <a href="#" class="hover:text-[#ff8a8a] transition-colors">Linkedin</a>
            </li>
            <li class="flex items-center group">
              <span class="w-7 h-7 rounded-full bg-white text-[#ff8a8a] flex items-center justify-center mr-3 group-hover:bg-[#ff8a8a] group-hover:text-white transition-colors shadow-sm"><i class="fab fa-pinterest-p text-[10px]"></i></span>
              <a href="#" class="hover:text-[#ff8a8a] transition-colors">Pinterest</a>
            </li>
            <li class="flex items-center group">
              <span class="w-7 h-7 rounded-full bg-white text-[#ff8a8a] flex items-center justify-center mr-3 group-hover:bg-[#ff8a8a] group-hover:text-white transition-colors shadow-sm"><i class="fab fa-youtube text-[10px]"></i></span>
              <a href="#" class="hover:text-[#ff8a8a] transition-colors">Youtube</a>
            </li>
          </ul>
        </div>
      </div>
    </div>

    <!-- Copyright Bottom Bar -->
    <div class="bg-white py-5 relative border-t border-gray-100 flex items-center justify-center">
      <p class="text-[10px] text-gray-500 tracking-[0.2em] uppercase">
        Copyright © 2026 <span class="font-bold text-[#222]">Beautifo</span>. All Rights Reserved.
      </p>
      
      <!-- Floating Back to Top Button -->
      <button @click="scrollToTop" class="absolute right-6 lg:right-10 w-12 h-12 bg-[#ff8a8a] hover:bg-[#222] text-white rounded-full flex flex-col items-center justify-center transition-all duration-300 shadow-lg group z-50 transform hover:-translate-y-1" aria-label="Back to top">
        <i class="fas fa-chevron-up text-[10px] mb-0.5"></i>
        <span class="text-[8px] font-bold uppercase tracking-widest">Top</span>
      </button>
    </div>
  </footer>
</template>

<script setup>
const scrollToTop = () => {
  window.scrollTo({ top: 0, behavior: 'smooth' })
}
</script>
