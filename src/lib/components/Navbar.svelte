<script lang="ts">
  import { page } from '$app/stores';
</script>

<nav class="bg-black text-white py-4 px-6 flex items-center justify-between sticky top-0 z-50 border-b border-gray-900">
  <div class="flex items-center gap-8">
    <a href="/" class="text-2xl font-medium tracking-tight">Ward-Smith Interiors</a>
    
    <div class="hidden md:flex items-center gap-6 text-[13px] font-medium text-gray-300">
      <a href="#wardrobes" class="hover:text-white transition-colors">Wardrobes</a>
      <a href="#kitchens" class="hover:text-white transition-colors">Kitchens</a>
      <a href="#how-it-works" class="hover:text-white transition-colors">How it works</a>
      <a href="#gallery" class="hover:text-white transition-colors">Gallery</a>
      <a href="#about" class="hover:text-white transition-colors">About</a>
    </div>
  </div>

  <div class="flex items-center gap-4">
    <a href="tel:+44" class="text-gray-300 hover:text-white transition-colors">
      <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
    </a>
    <a href="#contact" class="bg-primary-600 hover:bg-primary-700 text-white px-4 py-2 rounded-full text-[13px] font-medium transition-colors">
      Free consultation
    </a>
  </div>
</nav>
