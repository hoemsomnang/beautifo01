<template>
  <main class="w-full">
    <!-- Header Banner -->
    <div class="relative bg-[#f5f5f5] py-24 lg:py-32 overflow-hidden flex items-center justify-center">
      <div class="absolute inset-0 z-0">
        <img src="https://images.unsplash.com/photo-1556228578-0d85b1a4d571?auto=format&fit=crop&q=80&w=2000" alt="Contact Us Banner" class="w-full h-full object-cover opacity-30 mix-blend-multiply blur-[2px]">
      </div>
      <div class="relative z-10 text-center px-6">
        <h1 class="serif-font text-5xl lg:text-6xl text-black mb-4 font-bold tracking-tight">We Here To Help</h1>
        <div class="text-[10px] uppercase font-bold tracking-[0.2em] text-gray-500">
          <router-link to="/" class="hover:text-pink-accent transition-colors">Beautifo</router-link> 
          <span class="mx-2">&gt;</span> 
          <span class="text-gray-900">Contact us</span>
        </div>
      </div>
    </div>

    <!-- Our Address Section -->
    <section class="bg-[#f8f4f2] py-24">
      <div class="max-w-7xl mx-auto px-6 text-center">
        <p class="text-[10px] font-bold uppercase tracking-[0.2em] text-[#ff8a8a] mb-4">Contact Info</p>
        <h2 class="serif-font text-4xl lg:text-5xl text-gray-900 mb-8 font-bold">Our Address</h2>
        <p class="text-gray-500 text-sm leading-relaxed max-w-2xl mx-auto mb-20">
          Beautifo brings minimalist, naturally-derived beauty to the modern world. We focus on curating collections that highlight your natural beauty without hiding it behind heavy, unnatural layers.
        </p>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-12 text-left">
          <!-- Location -->
          <div class="flex items-start gap-6 group">
            <div class="w-16 h-16 rounded-full bg-white shadow-sm flex items-center justify-center text-[#ff8a8a] flex-shrink-0 group-hover:bg-[#ff8a8a] group-hover:text-white transition-colors duration-300">
              <i class="fas fa-location-arrow text-xl"></i>
            </div>
            <div>
              <h3 class="text-lg font-bold text-gray-900 mb-2">Location</h3>
              <p class="text-gray-500 text-sm leading-relaxed">8814 Bayberry Ave.<br>Jonesborough, TN 37659</p>
            </div>
          </div>

          <!-- Support -->
          <div class="flex items-start gap-6 group">
            <div class="w-16 h-16 rounded-full bg-white shadow-sm flex items-center justify-center text-[#ff8a8a] flex-shrink-0 group-hover:bg-[#ff8a8a] group-hover:text-white transition-colors duration-300">
              <i class="fas fa-phone-alt text-xl"></i>
            </div>
            <div>
              <h3 class="text-lg font-bold text-gray-900 mb-2">Support</h3>
              <p class="text-gray-500 text-sm leading-relaxed mb-1">Mobile: +(84) - 1800 - 33355</p>
              <p class="text-gray-500 text-sm leading-relaxed">Support: 1800 - 33355</p>
            </div>
          </div>

          <!-- Get In Touch -->
          <div class="flex items-start gap-6 group">
            <div class="w-16 h-16 rounded-full bg-white shadow-sm flex items-center justify-center text-[#ff8a8a] flex-shrink-0 group-hover:bg-[#ff8a8a] group-hover:text-white transition-colors duration-300">
              <i class="far fa-clock text-xl"></i>
            </div>
            <div>
              <h3 class="text-lg font-bold text-gray-900 mb-2">Get In Touch</h3>
              <p class="text-gray-500 text-sm leading-relaxed mb-1">Monday - Friday: 09:00 to 18:00 (GMT +8)</p>
              <p class="text-gray-500 text-sm leading-relaxed">Closed on Saturday & Sunday.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Map Section -->
    <div class="w-full h-[500px] bg-gray-200">
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d103328.71887375253!2d-115.25870020155073!3d36.12491845188899!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80beb782a4f57dd1%3A0x3accd5e6d5b379a3!2sLas%20Vegas%2C%20NV%2C%20USA!5e0!3m2!1sen!2s!4v1689823485093!5m2!1sen!2s" 
        class="w-full h-full border-0" 
        allowfullscreen="" 
        loading="lazy" 
        referrerpolicy="no-referrer-when-downgrade">
      </iframe>
    </div>

    <!-- Contact Form Section -->
    <section class="py-24 bg-white">
      <div class="max-w-4xl mx-auto px-6 text-center">
        <h2 class="serif-font text-4xl lg:text-5xl text-gray-900 mb-6 font-bold">Ready to Get Started?</h2>
        <p class="text-gray-500 text-sm leading-relaxed mb-16">
          Your email address will not be published. Required fields are marked *
        </p>

        <form class="space-y-6 text-left">
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
              <input type="text" placeholder="Your Name *" required class="w-full border border-gray-200 rounded-full px-6 py-4 bg-white shadow-sm focus:border-pink-accent focus:ring-1 focus:ring-pink-accent outline-none text-gray-600 text-sm transition-colors">
            </div>
            <div>
              <input type="tel" placeholder="Phone Number *" required class="w-full border border-gray-200 rounded-full px-6 py-4 bg-white shadow-sm focus:border-pink-accent focus:ring-1 focus:ring-pink-accent outline-none text-gray-600 text-sm transition-colors">
            </div>
          </div>
          
          <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            <div>
              <input type="email" placeholder="Email Address *" required class="w-full border border-gray-200 rounded-full px-6 py-4 bg-white shadow-sm focus:border-pink-accent focus:ring-1 focus:ring-pink-accent outline-none text-gray-600 text-sm transition-colors">
            </div>
            <div>
              <input type="text" placeholder="Subject" class="w-full border border-gray-200 rounded-full px-6 py-4 bg-white shadow-sm focus:border-pink-accent focus:ring-1 focus:ring-pink-accent outline-none text-gray-600 text-sm transition-colors">
            </div>
          </div>

          <div>
            <textarea rows="6" placeholder="Message *" required class="w-full border border-gray-200 rounded-3xl px-6 py-4 bg-white shadow-sm focus:border-pink-accent focus:ring-1 focus:ring-pink-accent outline-none text-gray-600 text-sm transition-colors resize-none"></textarea>
          </div>

          <div class="text-center pt-4">
            <button type="submit" class="bg-[#ff8a8a] hover:bg-[#111] text-white px-10 py-4 rounded-full font-bold text-[11px] uppercase tracking-widest transition-colors duration-300 shadow-xl inline-flex items-center">
              Send Message <i class="fas fa-angle-double-right text-[10px] ml-2"></i>
            </button>
          </div>
        </form>
      </div>
    </section>

  </main>
</template>

<script setup>
// Static layout
</script>
