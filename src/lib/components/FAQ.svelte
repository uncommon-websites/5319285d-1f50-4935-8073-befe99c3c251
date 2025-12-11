<script>
    const faqs = [
        "How does Bogi handle multiple tasks simultaneously?",
        "When will Bogi be available on mobile devices?",
        "What types of tasks can Bogi complete?",
        "Can I integrate Bogi with my existing tools and apps?",
        "What are Bogi's security and privacy standards?"
    ];
</script>

<section class="max-w-[1200px] mx-auto px-4 py-20">
    <h2 class="text-4xl md:text-5xl font-bold tracking-tight text-notion-black mb-12">
        Questions & answers
    </h2>

    <div class="border-t border-gray-200">
        {#each faqs as faq}
            <div class="border-b border-gray-200 py-6 flex justify-between items-center cursor-pointer group">
                <h3 class="font-medium text-notion-black text-sm md:text-base group-hover:text-notion-blue transition-colors">
                    {faq}
                </h3>
                <svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-notion-black group-hover:text-notion-blue transition-colors">
                    <line x1="12" y1="5" x2="12" y2="19"></line>
                    <line x1="5" y1="12" x2="19" y2="12"></line>
                </svg>
            </div>
        {/each}
    </div>
</section>
