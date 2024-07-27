<script>
    import 'preline'
</script>

<div class="container mx-auto">
    <div class="h-80 w-auto bg-slate-300">
        <!-- <h1 class="text-xl font-bold text-center self-center">CAROUSEL</h1> -->
         <!-- Slider -->
<div data-hs-carousel={`{
    "loadingClasses": "opacity-0",
    "isAutoPlay": true
  }`} class="relative">
  <div class="hs-carousel relative overflow-hidden w-full min-h-96 bg-white rounded-lg">
    <div class="hs-carousel-body absolute top-0 bottom-0 start-0 flex flex-nowrap transition-transform duration-700 opacity-0">
      <div class="hs-carousel-slide">
        <div class="flex justify-center h-full bg-gray-100 p-6">
          <span class="self-center text-4xl text-gray-800 transition duration-700">First slide</span>
        </div>
      </div>
      <div class="hs-carousel-slide">
        <div class="flex justify-center h-full bg-gray-200 p-6">
          <span class="self-center text-4xl text-gray-800 transition duration-700">Second slide</span>
        </div>
      </div>
      <div class="hs-carousel-slide">
        <div class="flex justify-center h-full bg-gray-300 p-6">
          <span class="self-center text-4xl text-gray-800 transition duration-700">Third slide</span>
        </div>
      </div>
    </div>
  </div>

  <button type="button" class="hs-carousel-prev hs-carousel:disabled:opacity-50 disabled:pointer-events-none absolute inset-y-0 start-0 inline-flex justify-center items-center w-[46px] h-full text-gray-800 hover:bg-gray-800/10 focus:outline-none focus:bg-gray-800/10 rounded-s-lg">
    <span class="text-2xl" aria-hidden="true">
      <svg class="shrink-0 size-5" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <path d="m15 18-6-6 6-6"></path>
      </svg>
    </span>
    <span class="sr-only">Previous</span>
  </button>
  <button type="button" class="hs-carousel-next hs-carousel:disabled:opacity-50 disabled:pointer-events-none absolute inset-y-0 end-0 inline-flex justify-center items-center w-[46px] h-full text-gray-800 hover:bg-gray-800/10 focus:outline-none focus:bg-gray-800/10 rounded-e-lg">
    <span class="sr-only">Next</span>
    <span class="text-2xl" aria-hidden="true">
      <svg class="shrink-0 size-5" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
        <path d="m9 18 6-6-6-6"></path>
      </svg>
    </span>
  </button>

  <div class="hs-carousel-pagination flex justify-center absolute bottom-3 start-0 end-0 space-x-2">
    <span class="hs-carousel-active:bg-blue-700 hs-carousel-active:border-blue-700 size-3 border border-gray-400 rounded-full cursor-pointer"></span>
    <span class="hs-carousel-active:bg-blue-700 hs-carousel-active:border-blue-700 size-3 border border-gray-400 rounded-full cursor-pointer"></span>
    <span class="hs-carousel-active:bg-blue-700 hs-carousel-active:border-blue-700 size-3 border border-gray-400 rounded-full cursor-pointer"></span>
  </div>
</div>
<!-- End Slider -->
    </div>
    <div class="my-3 p-2 h-auto w-auto bg-blue-300">
        <h1 class="text-xl font-bold text-center self-center">NEWS</h1>
        <div class="grid grid-cols-4 justify-between gap-4">
            <div class="flex flex-col bg-white border shadow-sm rounded-xl">
                <img class="w-full h-auto rounded-t-xl" src="https://images.unsplash.com/photo-1680868543815-b8666dba60f7?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=320&q=80" alt="Card Image">
                <div class="p-4 md:p-5">
                    <h3 class="text-lg font-bold text-gray-800">
                        Card 1
                    </h3>
                    <p class="mt-1 text-gray-500">
                        Some quick example text to build on the card title and make up the bulk of the card's content.
                    </p>
                    <a class="mt-2 py-2 px-3 inline-flex justify-center items-center gap-x-2 text-sm font-medium rounded-lg border border-transparent bg-blue-600 text-white hover:bg-blue-700 focus:outline-none focus:bg-blue-700 disabled:opacity-50 disabled:pointer-events-none" href="/">
                        Go somewhere
                    </a>
                </div>
            </div>
            <div class="flex flex-col bg-white border shadow-sm rounded-xl">
                <img class="w-full h-auto rounded-t-xl" src="https://images.unsplash.com/photo-1680868543815-b8666dba60f7?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=320&q=80" alt="Card Image">
                <div class="p-4 md:p-5">
                    <h3 class="text-lg font-bold text-gray-800">
                        Card 1
                    </h3>
                    <p class="mt-1 text-gray-500">
                        Some quick example text to build on the card title and make up the bulk of the card's content.
                    </p>
                    <a class="mt-2 py-2 px-3 inline-flex justify-center items-center gap-x-2 text-sm font-medium rounded-lg border border-transparent bg-blue-600 text-white hover:bg-blue-700 focus:outline-none focus:bg-blue-700 disabled:opacity-50 disabled:pointer-events-none" href="/">
                        Go somewhere
                    </a>
                </div>
            </div>
            <div class="flex flex-col bg-white border shadow-sm rounded-xl">
                <img class="w-full h-auto rounded-t-xl" src="https://images.unsplash.com/photo-1680868543815-b8666dba60f7?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=320&q=80" alt="Card Image">
                <div class="p-4 md:p-5">
                    <h3 class="text-lg font-bold text-gray-800">
                        Card 1
                    </h3>
                    <p class="mt-1 text-gray-500">
                        Some quick example text to build on the card title and make up the bulk of the card's content.
                    </p>
                    <a class="mt-2 py-2 px-3 inline-flex justify-center items-center gap-x-2 text-sm font-medium rounded-lg border border-transparent bg-blue-600 text-white hover:bg-blue-700 focus:outline-none focus:bg-blue-700 disabled:opacity-50 disabled:pointer-events-none" href="/">
                        Go somewhere
                    </a>
                </div>
            </div>
            <div class="flex flex-col bg-white border shadow-sm rounded-xl">
                <img class="w-full h-auto rounded-t-xl" src="https://images.unsplash.com/photo-1680868543815-b8666dba60f7?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=320&q=80" alt="Card Image">
                <div class="p-4 md:p-5">
                    <h3 class="text-lg font-bold text-gray-800">
                        Card 1
                    </h3>
                    <p class="mt-1 text-gray-500">
                        Some quick example text to build on the card title and make up the bulk of the card's content.
                    </p>
                    <a class="mt-2 py-2 px-3 inline-flex justify-center items-center gap-x-2 text-sm font-medium rounded-lg border border-transparent bg-blue-600 text-white hover:bg-blue-700 focus:outline-none focus:bg-blue-700 disabled:opacity-50 disabled:pointer-events-none" href="/">
                        Go somewhere
                    </a>
                </div>
            </div>
        </div>
    </div>
    <div class="grid gap-5 grid-cols-8 justify-between">
        <div class="col-span-2 p-4 bg-slate-100 border rounded-md shadow-md">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab repudiandae ipsum libero totam repellendus aut at atque cupiditate consequatur delectus velit quae dolore vitae a ut placeat, id quaerat eum.</p>
        </div>
        <div class="bg-blue-400 col-span-4 p-4 border rounded-md shadow-md">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error unde tempora, id provident repellat quis corporis similique, doloremque et architecto mollitia consequatur ratione deleniti quibusdam ducimus, dignissimos voluptatem numquam excepturi!</p>
        </div>
        <div class="col-end col-span-2 p-4 bg-slate-100 border rounded-md shadow-md">
            <h1 class="text-xl font-bold pb-2">EVENT</h1>
            <hr class="border mb-2 border-black">
            
            <!-- event card -->
            <!-- <div class="mb-2">
                <div class="flex flex-col bg-white border shadow-sm rounded-xl">
                    <div class="p-4 md:p-5">
                        <h3 class="text-lg font-bold text-gray-800">
                            Card title
                        </h3>
                        <p class="mt-2 text-gray-500">
                            With supporting text below as a natural lead-in to additional content.
                        </p>
                        <a class="mt-3 inline-flex items-center gap-x-1 text-sm font-semibold rounded-lg border border-transparent text-blue-600 decoration-2 hover:text-blue-700 hover:underline focus:underline focus:outline-none focus:text-blue-700 disabled:opacity-50 disabled:pointer-events-none" href="#">
                            Card link
                            <svg class="shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="m9 18 6-6-6-6"></path>
                            </svg>
                        </a>
                    </div>
                    <div class="bg-gray-100 border-t rounded-b-xl py-3 px-4 md:py-4 md:px-5">
                        <p class="mt-1 text-sm text-gray-500">
                            Last updated 5 mins ago
                        </p>
                    </div>
                </div>
            </div>
            <div class="mb-2">
                <div class="flex flex-col bg-white border shadow-sm rounded-xl">
                    <div class="p-4 md:p-5">
                        <h3 class="text-lg font-bold text-gray-800">
                            Card title
                        </h3>
                        <p class="mt-2 text-gray-500">
                            With supporting text below as a natural lead-in to additional content.
                        </p>
                        <a class="mt-3 inline-flex items-center gap-x-1 text-sm font-semibold rounded-lg border border-transparent text-blue-600 decoration-2 hover:text-blue-700 hover:underline focus:underline focus:outline-none focus:text-blue-700 disabled:opacity-50 disabled:pointer-events-none" href="#">
                            Card link
                            <svg class="shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="m9 18 6-6-6-6"></path>
                            </svg>
                        </a>
                    </div>
                    <div class="bg-gray-100 border-t rounded-b-xl py-3 px-4 md:py-4 md:px-5">
                        <p class="mt-1 text-sm text-gray-500">
                            Last updated 5 mins ago
                        </p>
                    </div>
                </div>
            </div>
            <div class="mb-2">
                <div class="flex flex-col bg-white border shadow-sm rounded-xl">
                    <div class="p-4 md:p-5">
                        <h3 class="text-lg font-bold text-gray-800">
                            Card title
                        </h3>
                        <p class="mt-2 text-gray-500">
                            With supporting text below as a natural lead-in to additional content.
                        </p>
                        <a class="mt-3 inline-flex items-center gap-x-1 text-sm font-semibold rounded-lg border border-transparent text-blue-600 decoration-2 hover:text-blue-700 hover:underline focus:underline focus:outline-none focus:text-blue-700 disabled:opacity-50 disabled:pointer-events-none" href="#">
                            Card link
                            <svg class="shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="m9 18 6-6-6-6"></path>
                            </svg>
                        </a>
                    </div>
                    <div class="bg-gray-100 border-t rounded-b-xl py-3 px-4 md:py-4 md:px-5">
                        <p class="mt-1 text-sm text-gray-500">
                            Last updated 5 mins ago
                        </p>
                    </div>
                </div>
            </div> -->
            
            <!-- Timeline -->
            <div>
                <!-- Heading -->
                <div class="ps-2 my-2 first:mt-0">
                    <h3 class="text-xs font-medium uppercase text-gray-500">
                        1 Aug, 2023
                    </h3>
                </div>
                <!-- End Heading -->
            
                <!-- Item -->
                <div class="flex gap-x-3 relative group rounded-lg hover:bg-gray-100">
                    <a class="absolute inset-0 z-[1]" href="/"></a>
            
                    <!-- Icon -->
                    <div class="relative last:after:hidden after:absolute after:top-0 after:bottom-0 after:start-3.5 after:w-px after:-translate-x-[0.5px] after:bg-gray-200">
                        <div class="relative z-10 size-7 flex justify-center items-center">
                        <div class="size-2 rounded-full bg-white border-2 border-gray-300 group-hover:border-gray-600"></div>
                        </div>
                    </div>
                    <!-- End Icon -->
            
                    <!-- Right Content -->
                    <div class="grow p-2 pb-8">
                        <h3 class="flex gap-x-1.5 font-semibold text-gray-800">
                        EVENT 1
                        </h3>
                        <p class="mt-1 text-sm text-gray-600">
                        blablablablabla
                        </p>
                        <button type="button" class="mt-1 -ms-1 p-1 relative z-10 inline-flex items-center gap-x-2 text-xs rounded-lg border border-transparent text-gray-500 hover:bg-white hover:shadow-sm disabled:opacity-50 disabled:pointer-events-none">
                        <img class="shrink-0 size-4 rounded-full" src="https://images.unsplash.com/photo-1659482633369-9fe69af50bfb?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8auto=format&fit=facearea&facepad=3&w=320&h=320&q=80" alt="Avatar">
                        James Collins
                        </button>
                    </div>
                    <!-- End Right Content -->
                </div>
                <!-- End Item -->
            
                <!-- Item -->
                <div class="flex gap-x-3 relative group rounded-lg hover:bg-gray-100">
                    <a class="absolute inset-0 z-[1]" href="#"></a>
            
                    <!-- Icon -->
                    <div class="relative last:after:hidden after:absolute after:top-0 after:bottom-0 after:start-3.5 after:w-px after:-translate-x-[0.5px] after:bg-gray-200">
                        <div class="relative z-10 size-7 flex justify-center items-center">
                        <div class="size-2 rounded-full bg-white border-2 border-gray-300 group-hover:border-gray-600"></div>
                        </div>
                    </div>
                    <!-- End Icon -->
            
                    <!-- Right Content -->
                    <div class="grow p-2 pb-8">
                        <h3 class="flex gap-x-1.5 font-semibold text-gray-800">
                        Release v5.2.0 quick bug fix 🐞
                        </h3>
                        <button type="button" class="mt-1 -ms-1 p-1 relative z-10 inline-flex items-center gap-x-2 text-xs rounded-lg border border-transparent text-gray-500 hover:bg-white hover:shadow-sm disabled:opacity-50 disabled:pointer-events-none">
                        <span class="flex shrink-0 justify-center items-center size-4 bg-white border border-gray-200 text-[10px] font-semibold uppercase text-gray-600 rounded-full">
                            A
                        </span>
                        Alex Gregarov
                        </button>
                    </div>
                    <!-- End Right Content -->
                </div>
                <!-- End Item -->
            
                <!-- Item -->
                <div class="flex gap-x-3 relative group rounded-lg hover:bg-gray-100">
                    <a class="absolute inset-0 z-[1]" href="#"></a>
            
                    <!-- Icon -->
                    <div class="relative last:after:hidden after:absolute after:top-0 after:bottom-0 after:start-3.5 after:w-px after:-translate-x-[0.5px] after:bg-gray-200">
                        <div class="relative z-10 size-7 flex justify-center items-center">
                        <div class="size-2 rounded-full bg-white border-2 border-sky-400 group-hover:border-blue-900"></div>
                        </div>
                    </div>
                    <!-- End Icon -->
            
                    <!-- Right Content -->
                    <div class="grow p-2 pb-8">
                        <h3 class="flex gap-x-1.5 font-semibold text-gray-800">
                        Marked "Install Charts" completed
                        </h3>
                        <p class="mt-1 text-sm text-gray-600">
                        Finally! You can check it out here.
                        </p>
                        <button type="button" class="mt-1 -ms-1 p-1 relative z-10 inline-flex items-center gap-x-2 text-xs rounded-lg border border-transparent text-gray-500 hover:bg-white hover:shadow-sm disabled:opacity-50 disabled:pointer-events-none">
                        <img class="shrink-0 size-4 rounded-full" src="https://images.unsplash.com/photo-1659482633369-9fe69af50bfb?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=facearea&facepad=3&w=320&h=320&q=80" alt="Avatar">
                        James Collins
                        </button>
                    </div>
                    <!-- End Right Content -->
                </div>
                <!-- End Item -->
            
                <!-- Heading -->
                <div class="ps-2 my-2 first:mt-0">
                <h3 class="text-xs font-medium uppercase text-gray-500">
                    31 Jul, 2023
                </h3>
                </div>
                <!-- End Heading -->
            
                <!-- Item -->
                <div class="flex gap-x-3 relative group rounded-lg hover:bg-gray-100">
                <a class="absolute inset-0 z-[1]" href="#"></a>
            
                <!-- Icon -->
                <div class="relative last:after:hidden after:absolute after:top-0 after:bottom-0 after:start-3.5 after:w-px after:-translate-x-[0.5px] after:bg-gray-200">
                    <div class="relative z-10 size-7 flex justify-center items-center">
                    <div class="size-2 rounded-full bg-white border-2 border-gray-300 group-hover:border-gray-600"></div>
                    </div>
                </div>
                <!-- End Icon -->
            
                <!-- Right Content -->
                <div class="grow p-2 pb-8">
                    <h3 class="flex gap-x-1.5 font-semibold text-gray-800">
                    Take a break ⛳️
                    </h3>
                    <p class="mt-1 text-sm text-gray-600">
                    Just chill for now... 😉
                    </p>
                </div>
                <!-- End Right Content -->
                </div>
                <!-- End Item -->
            </div>
            <!-- End Timeline -->
        </div>
    </div>
</div>