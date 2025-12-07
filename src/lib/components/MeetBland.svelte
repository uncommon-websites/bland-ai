<section class="bg-bg-light px-6 pb-24">
  <div class="max-w-[1400px] mx-auto bg-black text-white rounded-2xl overflow-hidden relative min-h-[400px] flex items-center">
    
    <div class="relative z-10 p-12 md:p-16 max-w-2xl">
      <h2 class="text-3xl md:text-4xl font-bold mb-6 leading-tight">
        Meet Bland. The fastest<br/>conversational AI in the world.
      </h2>
      <p class="text-gray-400 mb-8 max-w-md leading-relaxed">
        Learn why we're trusted by companies like Samsara, Snapchat, and Gallup to automate customer support, sales, and more.
      </p>
      <button class="flex items-center gap-2 font-bold hover:gap-3 transition-all">
        Talk to Sales <span>→</span>
      </button>
    </div>

    <!-- Abstract Dot Pattern Graphic (Right Side) -->
    <div class="absolute right-0 top-1/2 -translate-y-1/2 w-1/2 h-full hidden lg:flex items-center justify-center">
      <div class="grid grid-cols-12 gap-2 opacity-80">
         <!-- Simplified representation of the dot horse/animal -->
         {#each Array(100) as _, i}
            <div class="w-2 h-2 bg-white rounded-full opacity-{Math.random() > 0.5 ? '100' : '0'}"></div>
         {/each}
      </div>
    </div>
  </div>
</section>
