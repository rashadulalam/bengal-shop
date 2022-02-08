<template>

 <header class="bg-white py-4 shadow">
  <div class="container flex items-center mx-auto justify-between">
    <!--    logo area-->
    <div class="">
      <Logo />
    </div>
    <div class="min-w-max flex-shrink-0">
      <form action="" class="flex itmes-center border border-gray-200 rounded-full">
        <div class="place-self-center px-3 text-gray-400">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
        </svg>
        </div>
        <input type="text" class="px-4 py-2 w-96 min-w-max rounded-full focus:outline-none" placeholder="Search....">
        <button class="bs-bg-green text-white rounded-full px-6 py-2 m-1">Search</button>
      </form>
    </div>
    <div class="flex items-center space-x-5">
      <a href="" class="relative hover:text-yellow-500 transition ease-in duration-150">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
        </svg>
        <span class="w-4 h-4 mx-auto block text-center text-xs rounded-full bg-yellow-500 text-white absolute -top-4 right-0 ">6</span>
      </a>
      <a href="" class="relative hover:text-yellow-500 transition ease-in duration-150">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
        </svg>
        <span class="w-4 h-4 mx-auto block text-center text-xs rounded-full bg-yellow-500 text-white absolute -top-4 right-0 ">12</span>
      </a>
      <a href="" class="hover:text-yellow-500 transition ease-in duration-150 flex itemes-center ">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
        </svg>
        <div class="ml-2">Account</div>
      </a>
    </div>
  </div>
  <!-- header bottom -->
  <div class="container mt-6 mx-auto bg-white flex items-center justify-between">
      <!-- category -->
      <div>
        <button class="bs-bg-green uppercase rounded-full text-white px-8 py-2 flex">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h7" />
</svg> all categories <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
</svg>
          </button>
      </div>
      <!-- navigation -->
      <nav class="min-w-max w-90 flex items-center space-x-8">
        <nuxtLink to="/" class="mx-2 my-2 capitalize hover:text-yellow-500 hover:border-b-2 hover:border-yellow-500 leading-10 transition ease-in duration-150">Home</nuxtLink>
        <nuxtLink to="/" class="mx-2 my-2 capitalize hover:text-yellow-500 hover:border-b-2 hover:border-yellow-500 leading-10 transition ease-in duration-150">Shop</nuxtLink>
        <nuxtLink to="/" class="mx-2 my-2 capitalize hover:text-yellow-500 hover:border-b-2 hover:border-yellow-500 leading-10 transition ease-in duration-150">Pages</nuxtLink>
        <nuxtLink to="/blog" class="mx-2 my-2 capitalize hover:text-yellow-500 hover:border-b-2 hover:border-yellow-500 leading-10 transition ease-in duration-150">Blog</nuxtLink>
        <nuxtLink to="/contact" class="mx-2 my-2 capitalize hover:text-yellow-500 hover:border-b-2 hover:border-yellow-500 leading-10 transition ease-in duration-150">Contact</nuxtLink>
        <nuxtLink to="/" class="mx-2 my-2 capitalize hover:text-yellow-500 hover:border-b-2 hover:border-yellow-500 leading-10 transition ease-in duration-150">Track order</nuxtLink>
      </nav>
      <!-- special offer -->
      <div>
        <a href="" class="mx-2 my-2 capitalize font-medium text-yellow-500 transition ease-in duration-150">% Special Offers!</a>
      </div>
  </div>
 </header>
</template>
