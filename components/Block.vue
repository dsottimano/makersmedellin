<template>
    <section class="relative pb-24">
  <img class="hidden md:block absolute top-0 right-0 w-36 sm:w-1/2 lg:w-auto lg:h-full object-contain" src="nigodo-assets/background/background-orange-right.svg" alt="">
 
  <div class="container px-4 mx-auto relative">
    <div class="flex flex-wrap -mx-4">
      <div class="w-full lg:w-1/2 px-4 mb-12 lg:mb-0">
        <div class="lg:max-w-lg">
          <span class="text-xl md:text-2xl font-extrabold text-indigo-500">Section label</span>
          <h1 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold font-heading mt-1 mb-6">Business is only as good as its tools.</h1>
          <p class="text-xl md:text-2xl font-extrabold leading-8 mb-10">We’re different. Nogodo is the only SaaS business platform that lets you run your business on one platform, seamlessly across all digital channels.</p>
          <div class="flex flex-wrap -mx-2 mb-6">
            <div class="w-full md:w-auto lg:w-7/12 px-2 mb-2 md:mb-0">
              <input class="block w-full p-4 text-lg font-extrabold placeholder-indigo-900 shadow border-2 border-indigo-900 rounded" type="email" placeholder="hello@shuffle.dev">
            </div>
            <div class="w-full md:w-auto lg:w-5/12 px-2"><a class="inline-flex w-full md:w-auto items-center justify-center h-full py-4 px-5 leading-6 text-md text-white font-extrabold bg-indigo-800 hover:bg-indigo-900 border-3 border-indigo-900 rounded transition duration-200" href="#">Get Started</a></div>
          </div>
          <div class="flex flex-wrap items-center">
            <div class="flex mr-8 items-center">
              <img class="block w-6 h-6 mr-2 object-contain" src="nigodo-assets/circle-icon-green.svg" alt="">
              <span class="text-lg font-extrabold">No Credit Card required</span>
            </div>
            <div class="flex items-center">
              <img class="block w-6 h-6 mr-2 object-contain" src="nigodo-assets/circle-icon-green.svg" alt="">
              <span class="text-lg font-extrabold">Free updates</span>
            </div>
          </div>
        </div>
      </div>
      <div class="w-full lg:w-1/2 px-4">
        <img class="block h-128 lg:h-140 w-full xl:max-w-lg object-cover border-3 border-indigo-900 rounded-2xl shadow-lg" src="nigodo-assets/headers/palms.jpg" alt="">
      </div>
    </div>
  </div>
  <div class="hidden navbar-menu relative z-50">
    <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
    <nav class="fixed top-0 left-0 bottom-0 flex flex-col w-full md:w-5/6 max-w-sm py-8 px-8 bg-white border-r overflow-y-auto">
      <div class="flex items-center mb-8">
        <a class="mr-auto text-2xl font-bold leading-none" href="#">
          <img class="h-6" src="nigodo-assets/logo-nigodo.svg" alt="" width="auto">
        </a>
        <button class="navbar-close">
          <svg class="h-6 w-6 text-gray-500 cursor-pointer hover:text-gray-500" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
          </svg>
        </button>
      </div>
      <div class="my-auto">
        <ul class="py-10">
          <li class="mb-1"><a class="block p-4 text-lg font-extrabold hover:bg-gray-50 rounded" href="#">Product</a></li>
          <li class="mb-1"><a class="block p-4 text-lg font-extrabold hover:bg-gray-50 rounded" href="#">Features</a></li>
          <li class="mb-1"><a class="block p-4 text-lg font-extrabold hover:bg-gray-50 rounded" href="#">Pricing</a></li>
          <li class="mb-1"><a class="block p-4 text-lg font-extrabold hover:bg-gray-50 rounded" href="#">Resources</a></li>
        </ul>
      </div>
      <div><a class="block mb-6 text-center leading-6 text-lg font-extrabold hover:text-indigo-800" href="#">Log In</a><a class="block py-4 px-6 text-center leading-6 text-lg text-white font-extrabold bg-indigo-800 hover:bg-indigo-900 border-3 border-indigo-900 shadow rounded transition duration-200" href="#">Sign Up</a></div>
    </nav>
  </div>
</section>
</template>