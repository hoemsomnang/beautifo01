<template>
  <section class="grid grid-cols-1 md:grid-cols-3 gap-12 mb-24">
    <!-- Best Seller -->
    <div>
      <h3 class="text-xl font-bold text-gray-900 mb-8">Best Seller</h3>
      <div class="space-y-8">
        <div v-for="p in bestSellers" :key="p.name" class="flex items-center space-x-6">
          <div class="sidebar-product-img">
            <img src="https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-15-1.jpg" :alt="p.name" class="w-2/3 h-2/3 object-contain mix-blend-multiply">
          </div>
          <div>
            <h4 class="text-[13px] font-medium text-gray-800 mb-1 leading-snug">{{ p.name }}</h4>
            <div class="flex text-[9px] text-pink-accent mb-2 space-x-0.5">
              <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star text-gray-200"></i>
            </div>
            <div class="text-[13px] space-x-2">
              <span class="font-bold text-gray-900">£{{ p.price }}</span>
              <span class="text-gray-400 line-through text-[11px]">£{{ p.oldPrice }}</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Top Rated -->
    <div>
      <h3 class="text-xl font-bold text-gray-900 mb-8">Top Rated</h3>
      <div class="space-y-8">
        <div v-for="p in topRated" :key="p.name" class="flex items-center space-x-6">
          <div class="sidebar-product-img">
            <img src="https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-15-1.jpg" :alt="p.name" class="w-2/3 h-2/3 object-contain mix-blend-multiply">
          </div>
          <div>
            <h4 class="text-[13px] font-medium text-gray-800 mb-1 leading-snug">{{ p.name }}</h4>
            <div class="flex text-[9px] text-pink-accent mb-2 space-x-0.5">
              <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
            </div>
            <div class="text-[13px] space-x-2">
              <span class="font-bold text-gray-900">£{{ p.price }}</span>
              <span class="text-gray-400 line-through text-[11px]">£{{ p.oldPrice }}</span>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- On Sale -->
    <div>
      <h3 class="text-xl font-bold text-gray-900 mb-8">On Sale</h3>
      <div class="space-y-8">
        <div v-for="p in onSale" :key="p.name" class="flex items-center space-x-6">
          <div class="sidebar-product-img">
            <img src="https://demo2.themelexus.com/beautifo/wp-content/uploads/2021/04/product-15-1.jpg" :alt="p.name" class="w-2/3 h-2/3 object-contain mix-blend-multiply">
          </div>
          <div>
            <h4 class="text-[13px] font-medium text-gray-800 mb-1 leading-snug">{{ p.name }}</h4>
            <div class="flex text-[9px] text-pink-accent mb-2 space-x-0.5">
              <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star text-gray-200"></i>
            </div>
            <div class="text-[13px] space-x-2">
              <span class="font-bold text-gray-900">£{{ p.price }}</span>
              <span class="text-gray-400 line-through text-[11px]">£{{ p.oldPrice }}</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const bestSellers = [
  { name: "Kerastase Discipline Bain Fluidealiste", price: "116.00", oldPrice: "167.53" },
  { name: "Kiko Milano Smart Hydrating Foundation", price: "96.00", oldPrice: "121.54" },
  { name: "Rational Household Labor Supply - JSTOR", price: "118.00", oldPrice: "148.33" }
];

const topRated = [
  { name: "Hydrating Cream Mask 75ml tube", price: "84.00", oldPrice: "140.92" },
  { name: "Rational Household Labor Supply - JSTOR", price: "118.00", oldPrice: "148.33" },
  { name: "Serveware & Serving Dish Sets 75ml", price: "72.00", oldPrice: "120.28" }
];

const onSale = [
  { name: "florence by mills Mind Glowing Peel", price: "112.00", oldPrice: "160.93" },
  { name: "Serveware & Serving Dish Sets 75ml", price: "72.00", oldPrice: "120.28" },
  { name: "SOS Hydra Refreshing Hydration Mask", price: "109.00", oldPrice: "156.16" }
];
</script>
