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

<nav class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 {isScrolled ? 'bg-white/90 backdrop-blur-md border-b border-gray-100 py-3' : 'bg-transparent py-5'}">
  <div class="container-custom flex items-center justify-between">
    <div class="flex items-center gap-8">
      <a href="/" class="flex items-center gap-2 text-xl font-bold tracking-tight text-gray-900">
        <!-- Modern Logo Icon -->
        <svg width="28" height="28" viewBox="0 0 28 28" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-plain-green">
          <rect x="3" y="12" width="6" height="13" rx="1" fill="currentColor" opacity="0.4"/>
          <rect x="11" y="7" width="6" height="18" rx="1" fill="currentColor" opacity="0.7"/>
          <rect x="19" y="3" width="6" height="22" rx="1" fill="currentColor"/>
        </svg>
        progeto
      </a>
      
      <div class="hidden md:flex items-center gap-6 text-sm font-medium text-gray-600">
        <a href="#features" class="hover:text-gray-900 transition-colors">Features</a>
        <a href="#how-it-works" class="hover:text-gray-900 transition-colors">How It Works</a>
        <a href="#pricing" class="hover:text-gray-900 transition-colors">Pricing</a>
        <a href="#" class="hover:text-gray-900 transition-colors">Contact</a>
      </div>
    </div>

    <div class="flex items-center gap-3">
      <a href="#" class="px-3 py-1.5 text-xs font-semibold border border-gray-200 rounded text-gray-700 hover:border-gray-400 transition-colors uppercase tracking-wide">
        Login
      </a>
      <a href="#" class="px-3 py-1.5 text-xs font-semibold bg-plain-green text-white rounded hover:bg-green-400 transition-colors uppercase tracking-wide">
        Get Started
      </a>
    </div>
  </div>
</nav>
