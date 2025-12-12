<script lang="ts">
</script>

<section class="bg-[#f0efeb] py-24 px-6">
  <div class="max-w-[1200px] mx-auto">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-12 mb-24">
      <div>
        <h2 class="text-[40px] font-light text-gray-900 leading-tight mb-6">
          Beautiful furniture<br>that's kind to<br>the planet.
        </h2>
        <p class="text-gray-500 text-sm max-w-[300px]">
          We're committed to environmental responsibility. All our materials are sustainably sourced and either recycled or recyclable, ensuring your beautiful furniture doesn't cost the earth.
        </p>
      </div>

      <div class="grid grid-cols-2 gap-8">
        <div class="bg-white/50 p-8 rounded-xl border border-white/60">
          <div class="text-[40px] font-light mb-2">100%</div>
          <p class="text-gray-500 text-xs uppercase tracking-wide mb-4">sustainable</p>
          <p class="text-gray-400 text-[10px] leading-relaxed">
            All materials sustainably sourced with future recyclability in mind.
          </p>
        </div>
        <div class="bg-white/50 p-8 rounded-xl border border-white/60">
          <div class="text-[40px] font-light mb-2">5<span class="text-lg ml-1">yr</span></div>
          <p class="text-gray-500 text-xs uppercase tracking-wide mb-4">guarantee</p>
          <p class="text-gray-400 text-[10px] leading-relaxed">
            Quality built to last, backed by our comprehensive 5-year guarantee.
          </p>
        </div>
      </div>
    </div>

    <!-- Workshop Image -->
    <div class="w-full h-[500px] rounded-2xl overflow-hidden mb-8 relative">
      <img 
        src="https://images.unsplash.com/photo-1565538810643-b5bdb714032a?q=80&w=2074&auto=format&fit=crop" 
        alt="Sustainable materials" 
        class="w-full h-full object-cover"
      />
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <!-- Card 1 -->
      <div class="bg-[#fdfbf7] p-8 rounded-2xl min-h-[300px] flex flex-col justify-end">
        <h3 class="text-xl font-normal mb-2">Sustainably<br>sourced</h3>
        <p class="text-gray-500 text-xs leading-relaxed mb-4">
          Every material we use is carefully selected for sustainability, ensuring your furniture is as responsible as it is beautiful.
        </p>
        <a href="#" class="text-xs font-medium flex items-center gap-1">Learn more -></a>
      </div>

      <!-- Card 2 (Primary color) -->
      <div class="bg-primary-600 p-8 rounded-2xl min-h-[300px] flex flex-col justify-between text-white relative overflow-hidden group">
         <img 
            src="https://images.unsplash.com/photo-1581092918056-0c4c3acd3789?q=80&w=2070&auto=format&fit=crop" 
            class="absolute inset-0 w-full h-full object-cover opacity-30 mix-blend-overlay"
            alt="Workshop"
         />
         <div class="relative z-10 h-full flex flex-col justify-end">
            <h3 class="text-xl font-normal mb-2">Local craftsmanship</h3>
            <p class="text-white/90 text-xs leading-relaxed mb-4">
            Made in our Essex workshop, reducing carbon footprint and supporting local skilled craftsmen.
            </p>
            <a href="#" class="text-xs font-medium flex items-center gap-1">Visit workshop -></a>
        </div>
      </div>

      <!-- Card 3 (Green) -->
      <div class="bg-[#059669] p-8 rounded-2xl min-h-[300px] flex flex-col justify-between relative overflow-hidden text-white">
         <img 
            src="https://images.unsplash.com/photo-1542601906990-b4d3fb778b09?q=80&w=2013&auto=format&fit=crop" 
            class="absolute inset-0 w-full h-full object-cover opacity-20 mix-blend-overlay"
            alt="Recycling"
         />
         <div class="relative z-10 h-full flex flex-col justify-end">
            <h3 class="text-xl font-normal mb-2">Built to last</h3>
            <p class="text-white/90 text-xs leading-relaxed mb-4">
            Quality materials and expert craftsmanship mean furniture that lasts for decades, not years.
            </p>
            <a href="#" class="text-xs font-medium flex items-center gap-1">Our guarantee -></a>
        </div>
      </div>
    </div>
  </div>
</section>
