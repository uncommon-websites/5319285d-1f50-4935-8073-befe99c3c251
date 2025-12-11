<script>
    // Hero Component - Bogi Task Management
    const tasks = [
        { task: "Research gift ideas for Mom's birthday", status: "In Progress", category: "Personal", color: "purple" },
        { task: "Draft email to investors", status: "Complete", category: "Work", color: "blue" },
        { task: "Find restaurants for anniversary dinner", status: "In Progress", category: "Personal", color: "purple" },
        { task: "Schedule dentist appointment", status: "Waiting", category: "Personal", color: "purple" },
        { task: "Compare insurance quotes", status: "In Progress", category: "Finance", color: "green" },
        { task: "Plan weekend trip itinerary", status: "In Progress", category: "Travel", color: "orange" },
        { task: "Research best laptop for coding", status: "Complete", category: "Shopping", color: "blue" },
        { task: "Find plumber for kitchen sink", status: "Waiting", category: "Home", color: "gray" },
    ];
</script>

<section class="pt-20 pb-16 px-4 flex flex-col items-center text-center max-w-[1200px] mx-auto">
    <!-- Parallel Tasks Icon -->
    <div class="mb-8 relative">
        <svg width="64" height="64" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-primary-600 w-20 h-20">
            <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M11.6277 5.74767C10.7109 6.38712 9.22456 6.38712 8.3078 5.74767C7.39104 5.10821 7.39104 4.07144 8.3078 3.43199C9.22456 2.79253 10.7109 2.79253 11.6277 3.43199C12.5445 4.07144 12.5445 5.10821 11.6277 5.74767ZM12.3486 9.68436C13.4488 10.4517 15.2324 10.4517 16.3325 9.68436C17.4326 8.91698 17.4326 7.67288 16.3325 6.90553C15.2324 6.13818 13.4488 6.13818 12.3486 6.90553C11.2485 7.67288 11.2485 8.91698 12.3486 9.68436ZM4.73651 16.6314C5.46993 17.143 6.65903 17.143 7.39246 16.6314C8.12584 16.1198 8.12584 15.2904 7.39246 14.7788C6.65903 14.2672 5.46993 14.2672 4.73651 14.7788C4.0031 15.2904 4.0031 16.1198 4.73651 16.6314ZM11.6277 13.1579C10.7109 13.7973 9.22456 13.7973 8.3078 13.1579C7.39104 12.5184 7.39104 11.4816 8.3078 10.8421C9.22456 10.2027 10.7109 10.2027 11.6277 10.8421C12.5445 11.4816 12.5445 12.5184 11.6277 13.1579ZM2.41254 12.6947C2.9626 13.0784 3.85443 13.0784 4.40449 12.6947C4.95455 12.311 4.95455 11.689 4.40449 11.3053C3.85443 10.9216 2.9626 10.9216 2.41254 11.3053C1.86248 11.689 1.86249 12.311 2.41254 12.6947ZM4.73651 9.22117C5.46992 9.73275 6.65902 9.73275 7.39246 9.22117C8.12584 8.7096 8.12584 7.88018 7.39246 7.36863C6.65902 6.85706 5.46992 6.85706 4.73651 7.36863C4.0031 7.88018 4.0031 8.7096 4.73651 9.22117ZM11.6277 20.568C10.7109 21.2075 9.22456 21.2075 8.3078 20.568C7.39104 19.9286 7.39104 18.8918 8.3078 18.2523C9.22456 17.6129 10.7109 17.6129 11.6277 18.2523C12.5445 18.8918 12.5445 19.9286 11.6277 20.568ZM17.191 13.3894C18.2911 14.1568 20.0748 14.1568 21.1749 13.3894C22.275 12.6221 22.275 11.3779 21.1749 10.6106C20.0748 9.84324 18.2911 9.84324 17.191 10.6106C16.0909 11.3779 16.0909 12.6221 17.191 13.3894ZM16.3325 17.0945C15.2324 17.8618 13.4488 17.8618 12.3486 17.0945C11.2485 16.3271 11.2485 15.083 12.3486 14.3156C13.4488 13.5483 15.2324 13.5483 16.3325 14.3156C17.4326 15.083 17.4326 16.3271 16.3325 17.0945Z"
                fill="currentColor"
            />
        </svg>
    </div>

    <h1 class="text-5xl md:text-6xl lg:text-7xl font-bold tracking-tight text-notion-black mb-6 max-w-4xl text-balance leading-[1.1]">
        Transform mental clutter <br class="hidden md:block" /> into completed tasks
    </h1>

    <p class="text-xl text-notion-gray max-w-2xl mb-10 text-balance leading-relaxed">
        Bogi is your AI assistant that executes multiple tasks in parallel. Just delegate and forget—get notified only when it matters.
    </p>

    <button class="bg-notion-black text-white text-lg font-medium px-6 py-3 rounded-[6px] hover:bg-gray-800 transition-colors mb-20">
        Join Early Access
    </button>

    <!-- UI Mockup -->
    <div class="w-full bg-white rounded-xl shadow-2xl border border-gray-200 overflow-hidden flex text-left text-sm h-[600px] relative">
        <!-- Sidebar -->
        <div class="w-64 bg-[#F7F7F5] border-r border-gray-200 p-4 flex flex-col gap-6 hidden md:flex">
            <div>
                <div class="flex items-center gap-2 px-2 py-1 mb-2 text-gray-500">
                    <div class="w-5 h-5 rounded-full bg-gray-300 flex items-center justify-center text-[10px] text-white font-bold">D</div>
                    <span class="font-medium text-notion-black">Doru</span>
                    <svg class="ml-auto w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M11 4H4a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7"></path><path d="M18.5 2.5a2.121 2.121 0 0 1 3 3L12 15l-4 1 1-4 9.5-9.5z"></path></svg>
                </div>
                
                <div class="relative">
                    <svg class="absolute left-2 top-1.5 w-4 h-4 text-gray-400" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="8"></circle><line x1="21" y1="21" x2="16.65" y2="16.65"></line></svg>
                    <input type="text" placeholder="Search" class="w-full bg-transparent pl-8 pr-2 py-1 text-sm outline-none placeholder-gray-400">
                </div>
            </div>

            <div>
                <div class="text-xs font-medium text-gray-500 px-2 mb-1">Categories</div>
                <div class="space-y-0.5">
                    <div class="flex items-center gap-2 px-2 py-1 bg-white rounded shadow-sm text-notion-black font-medium">
                        <svg class="w-4 h-4 text-primary-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path></svg>
                        All Tasks
                    </div>
                    <div class="flex items-center gap-2 px-2 py-1 text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
                        <svg class="w-4 h-4 text-purple-500" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><path d="M12 6v6l4 2"></path></svg>
                        In Progress
                    </div>
                     <div class="flex items-center gap-2 px-2 py-1 text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
                        <svg class="w-4 h-4 text-green-500" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path><polyline points="22 4 12 14.01 9 11.01"></polyline></svg>
                        Complete
                    </div>
                     <div class="flex items-center gap-2 px-2 py-1 text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
                        <svg class="w-4 h-4 text-orange-500" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><line x1="12" y1="8" x2="12" y2="12"></line><line x1="12" y1="16" x2="12.01" y2="16"></line></svg>
                        Waiting
                    </div>
                </div>
            </div>

             <div>
                <div class="text-xs font-medium text-gray-500 px-2 mb-1">Contexts</div>
                <div class="space-y-0.5">
                    <div class="flex items-center gap-2 px-2 py-1 text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
                        <span class="w-4 h-4 flex items-center justify-center text-purple-500">💜</span>
                        Personal
                    </div>
                    <div class="flex items-center gap-2 px-2 py-1 text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
                        <span class="w-4 h-4 flex items-center justify-center text-blue-500">💼</span>
                        Work
                    </div>
                    <div class="flex items-center gap-2 px-2 py-1 text-gray-600 hover:bg-gray-200 rounded cursor-pointer">
                        <span class="w-4 h-4 flex items-center justify-center text-orange-500">✈️</span>
                        Travel
                    </div>
                </div>
            </div>
        </div>

        <!-- Main Content -->
        <div class="flex-1 flex flex-col min-w-0 bg-white">
            <div class="h-12 border-b border-gray-100 flex items-center px-6 justify-between">
                <div class="flex items-center gap-2 font-medium text-notion-black">
                    <svg class="w-4 h-4 text-primary-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path></svg>
                    All Tasks
                </div>
                <div class="flex items-center gap-3 text-gray-400">
                    <div class="flex items-center gap-1 text-xs font-medium text-gray-500">
                        <svg class="w-3 h-3 text-primary-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path></svg>
                        5 running in parallel
                    </div>
                </div>
            </div>

            <div class="flex-1 overflow-auto">
                <table class="w-full text-left border-collapse">
                    <thead class="text-gray-400 text-xs font-normal border-b border-gray-100">
                        <tr>
                            <th class="py-2 pl-6 pr-4 font-normal w-[25%]"></th>
                            <th class="py-2 px-4 font-normal w-[50%]"></th>
                            <th class="py-2 px-4 font-normal w-[25%]"></th>
                        </tr>
                    </thead>
                    <tbody class="text-sm">
                        {#each tasks as task}
                            <tr class="group hover:bg-gray-50 border-b border-gray-50 last:border-0 transition-colors">
                                <td class="py-3 pl-6 pr-4 text-notion-black truncate">{task.task}</td>
                                <td class="py-3 px-4 text-gray-600 truncate">
                                    <span class="inline-flex items-center px-2 py-0.5 rounded text-xs font-medium
                                        {task.status === 'In Progress' ? 'bg-purple-100 text-purple-700' : ''}
                                        {task.status === 'Complete' ? 'bg-green-100 text-green-700' : ''}
                                        {task.status === 'Waiting' ? 'bg-orange-100 text-orange-700' : ''}
                                    ">
                                        {task.status}
                                    </span>
                                </td>
                                <td class="py-3 px-4 text-right">
                                    <span class="inline-flex items-center px-1.5 py-0.5 rounded text-xs font-medium
                                        {task.color === 'purple' ? 'bg-purple-50 text-purple-600' : ''}
                                        {task.color === 'blue' ? 'bg-blue-50 text-blue-600' : ''}
                                        {task.color === 'green' ? 'bg-green-50 text-green-600' : ''}
                                        {task.color === 'orange' ? 'bg-orange-50 text-orange-600' : ''}
                                        {task.color === 'gray' ? 'bg-gray-50 text-gray-600' : ''}
                                    ">
                                        {task.category}
                                    </span>
                                </td>
                            </tr>
                        {/each}
                    </tbody>
                </table>
            </div>
            
            <!-- Floating Action Button -->
            <div class="absolute bottom-8 right-8 bg-primary-600 hover:bg-primary-700 text-white px-4 py-2 rounded-full shadow-lg flex items-center gap-2 cursor-pointer transition-all z-10">
                Add new task
                 <div class="w-8 h-8 bg-white rounded-full flex items-center justify-center ml-1">
                    <svg class="w-4 h-4 text-primary-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="12" y1="5" x2="12" y2="19"></line><line x1="5" y1="12" x2="19" y2="12"></line></svg>
                </div>
            </div>
        </div>
    </div>
</section>
