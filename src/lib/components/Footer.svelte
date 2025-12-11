<script lang="ts">
	const links = {
		Product: ["Features", "How it works", "Roadmap", "Early access"],
		Company: ["About", "Blog", "Careers"],
		Resources: ["Help center", "FAQ", "Privacy policy", "Terms of service"],
		Connect: ["Twitter", "LinkedIn", "Email us"]
	};
</script>

<footer class="border-t border-notion-border py-16 px-4 md:px-8 lg:px-16 bg-white text-[14px]">
	<div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-6 gap-8">
		<div class="lg:col-span-2 flex flex-col gap-6">
			<div class="flex items-center gap-2">
				<svg width="30" height="30" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-primary-600">
					<path
						fill-rule="evenodd"
						clip-rule="evenodd"
						d="M11.6277 5.74767C10.7109 6.38712 9.22456 6.38712 8.3078 5.74767C7.39104 5.10821 7.39104 4.07144 8.3078 3.43199C9.22456 2.79253 10.7109 2.79253 11.6277 3.43199C12.5445 4.07144 12.5445 5.10821 11.6277 5.74767ZM12.3486 9.68436C13.4488 10.4517 15.2324 10.4517 16.3325 9.68436C17.4326 8.91698 17.4326 7.67288 16.3325 6.90553C15.2324 6.13818 13.4488 6.13818 12.3486 6.90553C11.2485 7.67288 11.2485 8.91698 12.3486 9.68436ZM4.73651 16.6314C5.46993 17.143 6.65903 17.143 7.39246 16.6314C8.12584 16.1198 8.12584 15.2904 7.39246 14.7788C6.65903 14.2672 5.46993 14.2672 4.73651 14.7788C4.0031 15.2904 4.0031 16.1198 4.73651 16.6314ZM11.6277 13.1579C10.7109 13.7973 9.22456 13.7973 8.3078 13.1579C7.39104 12.5184 7.39104 11.4816 8.3078 10.8421C9.22456 10.2027 10.7109 10.2027 11.6277 10.8421C12.5445 11.4816 12.5445 12.5184 11.6277 13.1579ZM2.41254 12.6947C2.9626 13.0784 3.85443 13.0784 4.40449 12.6947C4.95455 12.311 4.95455 11.689 4.40449 11.3053C3.85443 10.9216 2.9626 10.9216 2.41254 11.3053C1.86248 11.689 1.86249 12.311 2.41254 12.6947ZM4.73651 9.22117C5.46992 9.73275 6.65902 9.73275 7.39246 9.22117C8.12584 8.7096 8.12584 7.88018 7.39246 7.36863C6.65902 6.85706 5.46992 6.85706 4.73651 7.36863C4.0031 7.88018 4.0031 8.7096 4.73651 9.22117ZM11.6277 20.568C10.7109 21.2075 9.22456 21.2075 8.3078 20.568C7.39104 19.9286 7.39104 18.8918 8.3078 18.2523C9.22456 17.6129 10.7109 17.6129 11.6277 18.2523C12.5445 18.8918 12.5445 19.9286 11.6277 20.568ZM17.191 13.3894C18.2911 14.1568 20.0748 14.1568 21.1749 13.3894C22.275 12.6221 22.275 11.3779 21.1749 10.6106C20.0748 9.84324 18.2911 9.84324 17.191 10.6106C16.0909 11.3779 16.0909 12.6221 17.191 13.3894ZM16.3325 17.0945C15.2324 17.8618 13.4488 17.8618 12.3486 17.0945C11.2485 16.3271 11.2485 15.083 12.3486 14.3156C13.4488 13.5483 15.2324 13.5483 16.3325 14.3156C17.4326 15.083 17.4326 16.3271 16.3325 17.0945Z"
						fill="currentColor"
					/>
				</svg>
				<span class="font-semibold text-xl tracking-tight text-notion-black">bogi</span>
			</div>
			
			<div class="flex gap-4 text-notion-gray">
				<!-- Social Icons -->
				<a href="#" aria-label="Instagram"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg></a>
				<a href="#" aria-label="Twitter"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 4s-.7 2.1-2 3.4c1.6 10-9.4 17.3-18 11.6 2.2.1 4.4-.6 6-2C3 15.5.5 9.6 3 5c2.2 2.6 5.6 4.1 9 4-.9-4.2 4-6.6 7-3.8 1.1 0 3-1.2 3-1.2z"></path></svg></a>
				<a href="#" aria-label="LinkedIn"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg></a>
				<a href="#" aria-label="Facebook"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"></path></svg></a>
				<a href="#" aria-label="YouTube"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22.54 6.42a2.78 2.78 0 0 0-1.94-2C18.88 4 12 4 12 4s-6.88 0-8.6.46a2.78 2.78 0 0 0-1.94 2A29 29 0 0 0 1 11.75a29 29 0 0 0 .46 5.33A2.78 2.78 0 0 0 3.4 19c1.72.46 8.6.46 8.6.46s6.88 0 8.6-.46a2.78 2.78 0 0 0 1.94-2 29 29 0 0 0 .46-5.33 29 29 0 0 0-.46-5.33z"></path><polygon points="9.75 15.02 15.5 11.75 9.75 8.48 9.75 15.02"></polygon></svg></a>
			</div>

			<div class="mt-4">
				<button class="flex items-center gap-2 bg-gray-100 hover:bg-gray-200 px-3 py-2 rounded text-notion-gray transition-colors">
					<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"></circle><line x1="2" y1="12" x2="22" y2="12"></line><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"></path></svg>
					English (US)
					<svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="6 9 12 15 18 9"></polyline></svg>
				</button>
			</div>

            <div class="mt-auto pt-8 text-gray-500 text-xs">
                <p>Do Not Sell or Share My Info</p>
                <p class="mt-1">Cookie settings</p>
                <p class="mt-4">© 2025 Bogi. All rights reserved.</p>
            </div>
		</div>

		{#each Object.entries(links) as [category, items]}
			<div class="flex flex-col gap-3">
				<h3 class="font-semibold text-notion-black mb-1">{category}</h3>
				{#each items as item}
					<a href="#" class="text-notion-gray hover:text-primary-600 hover:underline transition-colors">{item}</a>
				{/each}
			</div>
		{/each}
	</div>
</footer>
