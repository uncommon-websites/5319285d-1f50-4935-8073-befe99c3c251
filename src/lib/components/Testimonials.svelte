<script>
    // Testimonials Component
    const testimonials = [
        {
            name: "Sarah Chen",
            handle: "@sarahchen",
            text: "Bogi transformed how I manage my life. I delegate tasks in the morning and by evening, everything's done. It's like having a personal assistant who never sleeps."
        },
        {
            name: "Marcus Rodriguez",
            handle: "@marcusr",
            text: "The parallel execution is a game-changer. I can finally get through my mental to-do list without feeling overwhelmed."
        },
        {
            name: "Emily Watson",
            handle: "@emilywatson",
            text: "I used to drop so many balls juggling work and personal tasks. Bogi catches them all. The smart notifications mean I'm never bothered unless it matters."
        },
        {
            name: "David Park",
            handle: "@davidpark",
            text: "Finally, an AI tool that actually reduces my cognitive load instead of adding to it. Bogi just gets it done."
        }
    ];
</script>

<section class="py-16 overflow-hidden">
    <div class="flex gap-6 overflow-x-auto px-4 pb-8 md:justify-center no-scrollbar snap-x">
        {#each testimonials as t}
            <div class="flex-none w-[300px] md:w-[350px] p-6 bg-white border border-gray-100 rounded-xl shadow-sm snap-center">
                <div class="flex flex-col gap-4 h-full">
                    <div>
                        <div class="font-medium text-notion-black">{t.name}</div>
                        <div class="text-gray-400 text-sm">{t.handle}</div>
                    </div>
                    <p class="text-notion-gray text-[15px] leading-relaxed">
                        {t.text}
                    </p>
                </div>
            </div>
        {/each}
        <!-- Add a fade effect or just let it scroll. The screenshot shows them cut off on the right, implying scroll or just a grid. -->
    </div>
</section>

<style>
    .no-scrollbar::-webkit-scrollbar {
        display: none;
    }
    .no-scrollbar {
        -ms-overflow-style: none;
        scrollbar-width: none;
    }
</style>
