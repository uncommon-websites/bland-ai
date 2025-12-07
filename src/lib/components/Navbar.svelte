<script>
  import { onMount } from 'svelte';

  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 10;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<nav class="fixed top-0 left-0 w-full z-50 transition-all duration-300 {isScrolled ? 'bg-bg-dark/90 backdrop-blur-md py-4' : 'bg-transparent py-6'}">
  <div class="max-w-[1400px] mx-auto px-6 flex items-center justify-between">
    <!-- Logo -->
    <a href="/" class="text-2xl font-bold tracking-tighter text-white">
      Bland<sup class="text-xs align-top top-0">®</sup>
    </a>

    <!-- Links -->
    <div class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-300">
      <a href="#" class="hover:text-white transition-colors">How it Works</a>
      <div class="group relative cursor-pointer">
        <span class="flex items-center gap-1 hover:text-white transition-colors">Product <svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M1 1L5 5L9 1" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg></span>
      </div>
      <a href="#" class="hover:text-white transition-colors">Enterprises</a>
      <div class="group relative cursor-pointer">
        <span class="flex items-center gap-1 hover:text-white transition-colors">Resources <svg width="10" height="6" viewBox="0 0 10 6" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M1 1L5 5L9 1" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/></svg></span>
      </div>
    </div>

    <!-- Actions -->
    <div class="flex items-center gap-6 text-sm font-medium">
      <a href="#" class="hidden md:block text-gray-300 hover:text-white transition-colors">Sign Up</a>
      <a href="#" class="hidden md:block text-gray-300 hover:text-white transition-colors">Sign In</a>
      <a href="#" class="bg-white text-black px-4 py-2 rounded-full hover:bg-gray-200 transition-colors font-semibold">
        Talk to Us
      </a>
    </div>
  </div>
</nav>
