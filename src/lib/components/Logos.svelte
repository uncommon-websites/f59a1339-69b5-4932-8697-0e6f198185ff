<script>
  const logos = [
    { name: "Silva Construções", font: "font-serif font-bold" },
    { name: "COSTA OBRAS", font: "font-mono font-bold tracking-widest" },
    { name: "Almeida & Filhos", font: "font-sans font-bold" },
    { name: "Reforma Pro", font: "font-mono font-bold text-xl" },
    { name: "Construtora Lima", font: "font-sans font-bold italic" },
    { name: "BuildBrasil", font: "font-sans font-bold" },
    { name: "SANTOS ENGENHARIA", font: "font-sans font-light uppercase tracking-widest" },
    { name: "Oliveira Reformas", font: "font-sans font-bold tracking-tight" },
    { name: "MegaObra", font: "font-mono font-bold" },
    { name: "Pereira Construções", font: "font-sans font-black tracking-tighter" },
    { name: "Obra Certa", font: "font-sans font-bold" },
    { name: "Rodrigues & Cia", font: "font-serif italic font-bold" },
  ];
</script>

<section class="py-16 border-b border-gray-100">
  <div class="container-custom text-center">
    <p class="text-[10px] font-bold tracking-[0.2em] text-gray-400 uppercase mb-10">
      Trusted by contractors across Brazil
    </p>
    
    <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-x-8 gap-y-12 items-center justify-items-center opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
      {#each logos as logo}
        <div class="text-xl md:text-2xl text-gray-800 flex items-center justify-center w-full">
           <!-- Placeholder for actual SVG logos -->
           <span class="{logo.font}">{logo.name}</span>
        </div>
      {/each}
    </div>
  </div>
</section>
