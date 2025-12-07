<script>
  let phoneNumber = "";
</script>

<section class="relative pt-40 pb-20 px-6 bg-bg-dark text-white overflow-hidden">
  <div class="max-w-[1400px] mx-auto grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
    
    <!-- Left: Headline -->
    <div class="max-w-2xl">
      <h1 class="text-5xl md:text-[5.5rem] leading-[1.05] font-bold tracking-tight mb-8">
        Voice AI that makes every customer feel like a VIP.
      </h1>
    </div>

    <!-- Right: CTA -->
    <div class="flex flex-col items-start lg:items-end w-full">
      <div class="w-full max-w-md bg-[#111] p-1 rounded-lg border border-white/10">
        <div class="mb-4 px-2 pt-2">
          <h3 class="text-xl font-bold mb-1">Don't believe us?</h3>
          <p class="text-gray-400">Have Blandy give you a call.</p>
        </div>
        
        <div class="relative flex items-center bg-black rounded border border-white/10 p-1">
          <input 
            type="tel" 
            placeholder="Your Phone Number" 
            class="bg-transparent text-white px-4 py-3 w-full focus:outline-none placeholder:text-gray-600"
            bind:value={phoneNumber}
          />
          <button class="bg-primary hover:bg-primary-hover text-white px-6 py-2 rounded text-sm font-bold transition-colors whitespace-nowrap">
            Let's Talk
          </button>
        </div>
      </div>
    </div>
  </div>
</section>
