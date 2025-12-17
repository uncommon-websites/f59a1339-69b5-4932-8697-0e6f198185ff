<section class="py-12 bg-plain-dark">
  <div class="container-custom">
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      
      <!-- Card 1 -->
      <div class="bg-plain-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-center justify-center relative">
            <!-- Icons Grid -->
            <div class="grid grid-cols-4 gap-3 opacity-60 group-hover:opacity-100 transition-opacity">
                {#each Array(8) as _}
                <div class="w-8 h-8 rounded bg-gray-800 border border-gray-700"></div>
                {/each}
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">WhatsApp-native reporting</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          No new apps to learn. Your team already uses WhatsApp daily. Just send photos like you always do, and progeto handles the rest automatically.
        </p>
      </div>

      <!-- Card 2 -->
      <div class="bg-plain-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex items-end justify-center gap-1 pb-4">
            <!-- Bar Chart -->
            <div class="w-3 bg-green-900/40 h-12 rounded-t"></div>
            <div class="w-3 bg-green-800/60 h-16 rounded-t"></div>
            <div class="w-3 bg-green-700/80 h-10 rounded-t"></div>
            <div class="w-3 bg-green-600 h-24 rounded-t"></div>
            <div class="w-3 bg-green-500 h-20 rounded-t"></div>
            <div class="w-3 bg-green-400 h-28 rounded-t shadow-[0_0_15px_rgba(74,222,128,0.5)]"></div>
            <div class="w-3 bg-green-500 h-14 rounded-t"></div>
            <div class="w-3 bg-green-600 h-18 rounded-t"></div>
            
            <!-- Tooltip-like badge -->
            <div class="absolute top-10 bg-white text-black text-[10px] font-bold px-2 py-1 rounded shadow-lg transform translate-x-4">
                Negative shift
            </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Computer vision tracking</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Advanced AI identifies construction milestones from photos. Track foundation, framing, electrical, plumbing, and finishing automatically.
        </p>
      </div>

      <!-- Card 3 -->
      <div class="bg-plain-dark-secondary rounded-2xl p-8 border border-gray-800 hover:border-gray-700 transition-colors group">
        <div class="h-40 mb-8 flex flex-col items-center justify-center gap-3">
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-green-600 text-white text-xs rounded font-medium">Summarize thread</div>
                 <div class="px-3 py-1 bg-green-600/20 text-green-400 border border-green-600/30 text-xs rounded font-medium">Send docs</div>
             </div>
             <div class="flex gap-2">
                 <div class="px-3 py-1 bg-green-600/20 text-green-400 border border-green-600/30 text-xs rounded font-medium">Diagnose issue</div>
                 <div class="px-3 py-1 bg-green-600/20 text-green-400 border border-green-600/30 text-xs rounded font-medium">Draft reply</div>
             </div>
        </div>
        <h3 class="text-xl font-bold text-white mb-3">Professional progress reports</h3>
        <p class="text-gray-400 text-sm leading-relaxed">
          Generate client-ready reports instantly. Timeline views, milestone completion, photo galleries, and progress percentages—all automated.
        </p>
      </div>

    </div>
  </div>
</section>
