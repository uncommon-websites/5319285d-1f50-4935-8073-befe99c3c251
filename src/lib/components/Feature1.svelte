<section class="max-w-[1000px] mx-auto px-4 py-20" id="features">
    <div class="flex flex-col md:flex-row justify-between items-start mb-12">
        <h2 class="text-4xl md:text-5xl font-bold tracking-tight text-notion-black max-w-lg text-balance leading-[1.1]">
            Multiple tasks, executed in parallel.
        </h2>
        <!-- Parallel Tasks Illustration -->
        <div class="mt-8 md:mt-0 relative">
             <!-- Task 1 -->
            <svg width="60" height="60" viewBox="0 0 24 24" fill="none" stroke="oklch(0.623 0.214 259.815)" stroke-width="1.5" class="absolute -left-12 top-0 transform -rotate-12">
                <circle cx="12" cy="12" r="10"></circle>
                <path d="M12 6v6l4 2"></path>
                <rect x="1" y="1" width="22" height="22" rx="2" stroke-dasharray="2 2"></rect>
            </svg>
            <!-- Task 2 -->
             <svg width="60" height="60" viewBox="0 0 24 24" fill="none" stroke="oklch(0.623 0.214 259.815)" stroke-width="1.5" class="absolute left-4 top-4 transform rotate-6 z-10 bg-white">
                <circle cx="12" cy="12" r="10"></circle>
                <path d="M12 6v6l4 2"></path>
                 <rect x="1" y="1" width="22" height="22" rx="2" stroke-dasharray="2 2"></rect>
            </svg>
             <!-- Task 3 -->
             <svg width="60" height="60" viewBox="0 0 24 24" fill="none" stroke="oklch(0.623 0.214 259.815)" stroke-width="1.5" class="absolute left-20 -top-2 transform -rotate-6">
                <circle cx="12" cy="12" r="10"></circle>
                <path d="M12 6v6l4 2"></path>
                 <rect x="1" y="1" width="22" height="22" rx="2" stroke-dasharray="2 2"></rect>
            </svg>
        </div>
    </div>

    <div class="bg-[#F7F7F5] rounded-xl p-8 md:p-12 overflow-hidden relative min-h-[500px]">
        <!-- Background UI -->
        <div class="bg-white rounded-lg shadow-sm border border-gray-200 max-w-3xl mx-auto p-6 opacity-50 blur-[1px]">
            <div class="flex items-center justify-between mb-6">
                <div class="flex items-center gap-2 font-medium text-notion-black">
                    <svg class="w-5 h-5 text-red-500" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                    Inbox
                </div>
                <div class="flex items-center gap-2 border border-gray-200 rounded px-2 py-1 text-sm">
                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"></path><polyline points="7 10 12 15 17 10"></polyline><line x1="12" y1="15" x2="12" y2="3"></line></svg>
                    Auto label
                </div>
            </div>
            <div class="space-y-4">
                {#each [1, 2, 3, 4, 5] as i}
                    <div class="flex items-center gap-4">
                        <div class="w-24 h-3 bg-gray-100 rounded"></div>
                        <div class="flex-1 h-3 bg-gray-100 rounded"></div>
                    </div>
                {/each}
            </div>
        </div>

        <!-- Foreground Popover -->
        <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-full max-w-md bg-white rounded-xl shadow-2xl border border-gray-200 p-2 z-10">
            <div class="px-3 py-2 text-xs font-medium text-gray-500">Suggested</div>
            <div class="space-y-1">
                <div class="flex items-start gap-3 p-2 hover:bg-gray-50 rounded cursor-pointer">
                    <svg class="w-4 h-4 text-primary-600 mt-0.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><path d="M12 6v6l4 2"></path></svg>
                    <span class="text-sm text-notion-black">Research gift ideas for anniversary</span>
                </div>
                <div class="flex items-start gap-3 p-2 hover:bg-gray-50 rounded cursor-pointer">
                    <svg class="w-4 h-4 text-primary-600 mt-0.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><path d="M12 6v6l4 2"></path></svg>
                    <span class="text-sm text-notion-black">Draft email to potential investors</span>
                </div>
                <div class="flex items-start gap-3 p-2 hover:bg-gray-50 rounded cursor-pointer">
                    <svg class="w-4 h-4 text-primary-600 mt-0.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><path d="M12 6v6l4 2"></path></svg>
                    <span class="text-sm text-notion-black">Find and compare insurance quotes</span>
                </div>
            </div>
        </div>
    </div>

    <p class="mt-8 text-lg text-notion-black max-w-2xl">
        Delegate multiple tasks at once. Bogi executes them simultaneously, learning your preferences and context along the way.
    </p>
</section>
