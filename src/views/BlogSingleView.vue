<template>
  <main class="w-full">
    <!-- Page Banner -->
    <div class="relative bg-[#f9f5f3] py-20 lg:py-28 overflow-hidden mb-16">
      <div class="absolute inset-0 z-0">
        <!-- Subtle background texture/image -->
        <img src="https://images.unsplash.com/photo-1596462502278-27bfdc403348?auto=format&fit=crop&q=80&w=2000" alt="Blog Banner" class="w-full h-full object-cover opacity-10 blur-[1px]">
      </div>
      <div class="max-w-7xl mx-auto px-6 relative z-10 text-center">
        <div class="text-[10px] uppercase font-bold tracking-[0.2em] text-gray-500 mb-6">
          <router-link to="/" class="hover:text-pink-accent transition-colors">Home</router-link> 
          <span class="mx-2">&gt;</span> 
          <a href="#" class="hover:text-pink-accent transition-colors">Blog</a>
          <span class="mx-2">&gt;</span> 
          <a href="#" class="hover:text-pink-accent transition-colors">Beauty</a>
        </div>
        <h1 class="serif-font text-4xl lg:text-5xl font-bold text-gray-900 tracking-tight leading-tight max-w-4xl mx-auto">
          Tips & procedure to apply luxury beauty cosmetic cream
        </h1>
      </div>
    </div>

    <!-- Main Content & Sidebar -->
    <div class="max-w-7xl mx-auto px-6 pb-24">
      <div class="flex flex-col lg:flex-row gap-12">
        
        <!-- Main Content Area -->
        <article class="w-full lg:w-3/4">
          <!-- Featured Image -->
          <div class="rounded-3xl overflow-hidden mb-8 shadow-sm">
            <img src="https://images.unsplash.com/photo-1556228720-195a672e8a03?auto=format&fit=crop&q=80&w=1600" alt="Cosmetic Cream" class="w-full h-auto object-cover">
          </div>
          
          <!-- Meta Data -->
          <div class="flex items-center gap-4 text-[11px] font-bold uppercase tracking-widest text-gray-400 mb-8 border-b border-gray-100 pb-6">
            <span class="text-pink-accent">By Admin</span>
            <span class="w-1 h-1 rounded-full bg-gray-300"></span>
            <span>April 2, 2021</span>
            <span class="w-1 h-1 rounded-full bg-gray-300"></span>
            <span><i class="far fa-comment mr-1"></i> 2 Comments</span>
          </div>

          <!-- Body Content -->
          <div class="prose prose-lg max-w-none text-gray-600">
            <p class="leading-relaxed mb-6">
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
            </p>
            <p class="leading-relaxed mb-8">
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.
            </p>

            <blockquote class="border-l-4 border-pink-accent bg-[#fcfcfc] py-6 px-8 rounded-r-2xl mb-8">
              <p class="serif-font italic text-2xl text-gray-800 m-0 leading-relaxed">
                "Beauty begins the moment you decide to be yourself. Our goal is to enhance your natural glow, not mask it."
              </p>
            </blockquote>

            <h3 class="serif-font text-2xl font-bold text-gray-900 mb-4">The core principles of our routine</h3>
            <p class="leading-relaxed mb-6">
              Eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit.
            </p>

            <ul class="space-y-4 mb-10 pl-0">
              <li class="flex items-start gap-3">
                <i class="far fa-check-circle text-pink-accent mt-1 text-lg"></i>
                <span class="text-gray-600">Always cleanse before applying any serums or creams.</span>
              </li>
              <li class="flex items-start gap-3">
                <i class="far fa-check-circle text-pink-accent mt-1 text-lg"></i>
                <span class="text-gray-600">Use gentle upward motions to prevent skin sagging over time.</span>
              </li>
              <li class="flex items-start gap-3">
                <i class="far fa-check-circle text-pink-accent mt-1 text-lg"></i>
                <span class="text-gray-600">Lock in moisture with a reliable SPF during the daytime.</span>
              </li>
            </ul>
          </div>

          <!-- Tags & Share -->
          <div class="flex flex-col md:flex-row justify-between items-center py-6 border-y border-gray-100 mt-12 gap-4">
            <div class="flex items-center gap-3">
              <span class="text-[10px] font-bold uppercase tracking-widest text-gray-900">Tags:</span>
              <a href="#" class="text-[12px] text-gray-500 hover:text-pink-accent transition-colors">Cosmetics</a>,
              <a href="#" class="text-[12px] text-gray-500 hover:text-pink-accent transition-colors">Lifestyle</a>
            </div>
            <div class="flex items-center gap-4">
              <span class="text-[10px] font-bold uppercase tracking-widest text-gray-900">Share:</span>
              <div class="flex items-center gap-3 text-gray-400">
                <a href="#" class="hover:text-pink-accent transition-colors"><i class="fab fa-facebook-f"></i></a>
                <a href="#" class="hover:text-pink-accent transition-colors"><i class="fab fa-twitter"></i></a>
                <a href="#" class="hover:text-pink-accent transition-colors"><i class="fab fa-pinterest-p"></i></a>
                <a href="#" class="hover:text-pink-accent transition-colors"><i class="fab fa-linkedin-in"></i></a>
              </div>
            </div>
          </div>

          <!-- Post Navigation -->
          <div class="grid grid-cols-2 gap-8 py-10 border-b border-gray-100">
            <a href="#" class="group text-left border-r border-gray-100 pr-8">
              <span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mb-2 block group-hover:text-pink-accent transition-colors"><i class="fas fa-chevron-left mr-2"></i> Previous Post</span>
              <h4 class="text-lg font-bold text-gray-900 group-hover:text-pink-accent transition-colors line-clamp-2">The best part about makeup is brush and its types</h4>
            </a>
            <a href="#" class="group text-right pl-8">
              <span class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-400 mb-2 block group-hover:text-pink-accent transition-colors">Next Post <i class="fas fa-chevron-right ml-2"></i></span>
              <h4 class="text-lg font-bold text-gray-900 group-hover:text-pink-accent transition-colors line-clamp-2">Lightweight makeup to enhance your natural beauty</h4>
            </a>
          </div>

          <!-- Comments Section -->
          <div class="mt-16">
            <h3 class="serif-font text-2xl font-bold text-gray-900 mb-10">2 Comments</h3>
            
            <ul class="space-y-10 mb-16">
              <!-- Comment 1 -->
              <li class="flex gap-6">
                <img src="https://i.pravatar.cc/100?img=1" alt="Avatar" class="w-16 h-16 rounded-full object-cover">
                <div class="flex-1">
                  <div class="flex justify-between items-start mb-2">
                    <div>
                      <h5 class="text-[13px] font-bold text-gray-900 uppercase tracking-wider mb-1">Jane Doe</h5>
                      <p class="text-[11px] text-gray-400">April 3, 2021 at 10:24 am</p>
                    </div>
                    <button class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900 hover:text-pink-accent transition-colors">
                      <i class="fas fa-reply mr-1"></i> Reply
                    </button>
                  </div>
                  <p class="text-gray-600 text-[14px] leading-relaxed">
                    This was incredibly helpful! I've been looking for a solid routine to implement these creams properly. Thank you!
                  </p>
                </div>
              </li>
              
              <!-- Comment 2 (Reply) -->
              <li class="flex gap-6 ml-12">
                <img src="https://i.pravatar.cc/100?img=5" alt="Avatar" class="w-16 h-16 rounded-full object-cover">
                <div class="flex-1">
                  <div class="flex justify-between items-start mb-2">
                    <div>
                      <h5 class="text-[13px] font-bold text-gray-900 uppercase tracking-wider mb-1">Admin</h5>
                      <p class="text-[11px] text-gray-400">April 3, 2021 at 11:05 am</p>
                    </div>
                    <button class="text-[10px] font-bold uppercase tracking-[0.2em] text-gray-900 hover:text-pink-accent transition-colors">
                      <i class="fas fa-reply mr-1"></i> Reply
                    </button>
                  </div>
                  <p class="text-gray-600 text-[14px] leading-relaxed">
                    You're very welcome, Jane! We're thrilled to hear it helped.
                  </p>
                </div>
              </li>
            </ul>

            <!-- Leave a Reply -->
            <div class="bg-gray-50 p-8 md:p-12 rounded-3xl">
              <h3 class="serif-font text-2xl font-bold text-gray-900 mb-2">Leave a Reply</h3>
              <p class="text-gray-500 text-sm mb-8">Your email address will not be published. Required fields are marked *</p>
              
              <form class="space-y-6">
                <div>
                  <textarea rows="5" placeholder="Comment *" class="w-full border-none rounded-2xl px-6 py-4 bg-white shadow-sm focus:ring-2 focus:ring-pink-accent outline-none text-gray-600 text-sm resize-none"></textarea>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                  <input type="text" placeholder="Name *" class="w-full border-none rounded-full px-6 py-4 bg-white shadow-sm focus:ring-2 focus:ring-pink-accent outline-none text-gray-600 text-sm">
                  <input type="email" placeholder="Email *" class="w-full border-none rounded-full px-6 py-4 bg-white shadow-sm focus:ring-2 focus:ring-pink-accent outline-none text-gray-600 text-sm">
                </div>
                <div>
                  <input type="url" placeholder="Website" class="w-full border-none rounded-full px-6 py-4 bg-white shadow-sm focus:ring-2 focus:ring-pink-accent outline-none text-gray-600 text-sm">
                </div>
                <div class="flex items-center gap-3">
                  <input type="checkbox" id="save-info" class="w-4 h-4 accent-pink-accent rounded border-gray-300">
                  <label for="save-info" class="text-gray-500 text-sm">Save my name, email, and website in this browser for the next time I comment.</label>
                </div>
                <button type="button" class="bg-pink-accent hover:bg-black text-white px-10 py-4 rounded-full font-bold text-[11px] uppercase tracking-widest transition-colors duration-300 shadow-lg">
                  Post Comment
                </button>
              </form>
            </div>
          </div>
        </article>

        <!-- Sidebar -->
        <aside class="w-full lg:w-1/4">
          <!-- Search -->
          <div class="mb-12">
            <div class="relative">
              <input type="text" placeholder="Search..." class="w-full border border-gray-200 rounded-full px-6 py-3.5 text-sm outline-none focus:border-pink-accent text-gray-600 bg-white">
              <button class="absolute right-6 top-1/2 -translate-y-1/2 text-gray-400 hover:text-pink-accent"><i class="fas fa-search"></i></button>
            </div>
          </div>

          <!-- Categories -->
          <div class="mb-12">
            <h4 class="font-bold text-gray-900 text-lg mb-6 relative pb-4">
              Categories
              <span class="absolute bottom-0 left-0 w-8 h-0.5 bg-pink-accent"></span>
            </h4>
            <ul class="space-y-4 text-[13px] text-gray-600 font-medium">
              <li class="flex justify-between items-center group cursor-pointer">
                <span class="group-hover:text-pink-accent transition-colors"><i class="fas fa-angle-right text-[10px] mr-2 text-gray-400 group-hover:text-pink-accent opacity-0 group-hover:opacity-100 -translate-x-2 group-hover:translate-x-0 transition-all"></i> Beauty</span>
                <span class="text-gray-400 group-hover:text-pink-accent transition-colors">(3)</span>
              </li>
              <li class="flex justify-between items-center group cursor-pointer text-pink-accent">
                <span><i class="fas fa-angle-right text-[10px] mr-2"></i> Cosmetics</span>
                <span>(8)</span>
              </li>
              <li class="flex justify-between items-center group cursor-pointer">
                <span class="group-hover:text-pink-accent transition-colors"><i class="fas fa-angle-right text-[10px] mr-2 text-gray-400 group-hover:text-pink-accent opacity-0 group-hover:opacity-100 -translate-x-2 group-hover:translate-x-0 transition-all"></i> Lifestyle</span>
                <span class="text-gray-400 group-hover:text-pink-accent transition-colors">(12)</span>
              </li>
              <li class="flex justify-between items-center group cursor-pointer">
                <span class="group-hover:text-pink-accent transition-colors"><i class="fas fa-angle-right text-[10px] mr-2 text-gray-400 group-hover:text-pink-accent opacity-0 group-hover:opacity-100 -translate-x-2 group-hover:translate-x-0 transition-all"></i> Skincare</span>
                <span class="text-gray-400 group-hover:text-pink-accent transition-colors">(5)</span>
              </li>
            </ul>
          </div>

          <!-- Recent Posts -->
          <div class="mb-12">
            <h4 class="font-bold text-gray-900 text-lg mb-6 relative pb-4">
              Recent Posts
              <span class="absolute bottom-0 left-0 w-8 h-0.5 bg-pink-accent"></span>
            </h4>
            <div class="space-y-6">
              <div class="flex gap-4 group cursor-pointer">
                <img src="https://images.unsplash.com/photo-1556228720-195a672e8a03?auto=format&fit=crop&q=80&w=200" alt="Post" class="w-20 h-20 rounded-xl object-cover">
                <div>
                  <h5 class="text-[13px] font-bold text-gray-900 mb-2 leading-snug group-hover:text-pink-accent transition-colors line-clamp-2">Tips & procedure to apply luxury beauty cosmetic cream</h5>
                  <p class="text-[10px] font-bold uppercase tracking-widest text-gray-400">April 2, 2021</p>
                </div>
              </div>
              <div class="flex gap-4 group cursor-pointer">
                <img src="https://images.unsplash.com/photo-1612817288484-6f916006741a?auto=format&fit=crop&q=80&w=200" alt="Post" class="w-20 h-20 rounded-xl object-cover">
                <div>
                  <h5 class="text-[13px] font-bold text-gray-900 mb-2 leading-snug group-hover:text-pink-accent transition-colors line-clamp-2">The best part about makeup is brush and its types</h5>
                  <p class="text-[10px] font-bold uppercase tracking-widest text-gray-400">April 2, 2021</p>
                </div>
              </div>
              <div class="flex gap-4 group cursor-pointer">
                <img src="https://images.unsplash.com/photo-1556228578-0d85b1a4d571?auto=format&fit=crop&q=80&w=200" alt="Post" class="w-20 h-20 rounded-xl object-cover">
                <div>
                  <h5 class="text-[13px] font-bold text-gray-900 mb-2 leading-snug group-hover:text-pink-accent transition-colors line-clamp-2">Lightweight makeup to enhance your natural beauty</h5>
                  <p class="text-[10px] font-bold uppercase tracking-widest text-gray-400">April 2, 2021</p>
                </div>
              </div>
            </div>
          </div>

          <!-- Tags -->
          <div>
            <h4 class="font-bold text-gray-900 text-lg mb-6 relative pb-4">
              Tags
              <span class="absolute bottom-0 left-0 w-8 h-0.5 bg-pink-accent"></span>
            </h4>
            <div class="flex flex-wrap gap-2">
              <a href="#" class="bg-gray-100 hover:bg-pink-accent text-gray-600 hover:text-white text-[11px] px-4 py-2 rounded-full transition-colors">Beauty</a>
              <a href="#" class="bg-gray-100 hover:bg-pink-accent text-gray-600 hover:text-white text-[11px] px-4 py-2 rounded-full transition-colors">Cosmetics</a>
              <a href="#" class="bg-pink-accent text-white text-[11px] px-4 py-2 rounded-full transition-colors">Lifestyle</a>
              <a href="#" class="bg-gray-100 hover:bg-pink-accent text-gray-600 hover:text-white text-[11px] px-4 py-2 rounded-full transition-colors">Organic</a>
              <a href="#" class="bg-gray-100 hover:bg-pink-accent text-gray-600 hover:text-white text-[11px] px-4 py-2 rounded-full transition-colors">Skincare</a>
            </div>
          </div>
        </aside>

      </div>
    </div>
  </main>
</template>

<script setup>
</script>
