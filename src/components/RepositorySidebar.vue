<script setup lang="ts">
</script>

<template>
  <div class="sidebar w-full lg:w-1/4 mt-8 lg:mt-0">
    <!-- About Section -->
    <div class="mb-4">
      <div class="px-3 sm:px-4 py-3 border-b border-gray-400">
        <h3 class="font-semibold">About</h3>
      </div>
      <div class="px-3 sm:px-4 py-3">
        <p class="text-sm text-gray-700 mb-4">A utility-first CSS framework for rapid UI development.</p>
        <div class="space-y-2 text-sm">
          <a href="#" class="flex items-center space-x-2 text-blue-600 hover:underline">
            <svg class="w-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 008.716-6.747M12 21a9.004 9.004 0 01-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 017.843 4.582M12 3a8.997 8.997 0 00-7.843 4.582m15.686 0A11.953 11.953 0 0112 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0121 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0112 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 013 12c0-1.605.42-3.113 1.157-4.418" />
            </svg>
            <span>tailwindcss.com</span>
          </a>
        </div>
      </div>
      <div class="px-3 sm:px-4 py-3 border-t border-gray-400">
        <div class="flex flex-wrap items-center gap-2 sm:gap-4 text-xs sm:text-sm">
          <a href="#" class="flex items-center space-x-1 hover:text-blue-600">
            <svg class="w-3 sm:w-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M11.48 3.499a.562.562 0 011.04 0l2.125 5.111a.563.563 0 00.475.345l5.518.442c.499.04.701.663.321.988l-4.204 3.602a.563.563 0 00-.182.557l1.285 5.385a.562.562 0 01-.84.61l-4.725-2.885a.563.563 0 00-.586 0L6.982 20.54a.562.562 0 01-.84-.61l1.285-5.386a.562.562 0 00-.182-.557l-4.204-3.602a.563.563 0 01.321-.988l5.518-.442a.563.563 0 00.475-.345L11.48 3.5z" />
            </svg>
            <span class="font-semibold">25.2k</span>
            <span class="text-gray-600 hidden sm:inline">stars</span>
          </a>
          <a href="#" class="flex items-center space-x-1 hover:text-blue-600">
            <svg class="w-3 sm:w-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
              <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
            </svg>
            <span class="font-semibold">430</span>
            <span class="text-gray-600 hidden sm:inline">watching</span>
          </a>
          <a href="#" class="flex items-center space-x-1 hover:text-blue-600">
            <svg class="w-3 sm:w-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M7.5 21L3 16.5m0 0L7.5 12M3 16.5h13.5m0-13.5L21 7.5m0 0L16.5 12M21 7.5H7.5" />
            </svg>
            <span class="font-semibold">1.2k</span>
            <span class="text-gray-600 hidden sm:inline">forks</span>
          </a>
        </div>
      </div>
    </div>

    <!-- Releases Section -->
    <div class="rounded-md mb-4">
      <div class="px-3 sm:px-4 py-3 border-b border-gray-400 flex items-center justify-between">
        <h3 class="font-semibold text-base">Releases</h3>
        <span class="bg-gray-200 text-gray-700 text-xs font-semibold px-2 py-1 rounded-full">296</span>
      </div>
      <div class="px-3 sm:px-4 py-3">
        <div class="flex items-start space-x-2 mb-3">
          <svg class="w-4 mt-1 text-green-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9.568 3H5.25A2.25 2.25 0 003 5.25v4.318c0 .597.237 1.17.659 1.591l9.581 9.581c.699.699 1.78.872 2.607.33a18.095 18.095 0 005.223-5.223c.542-.827.369-1.908-.33-2.607L11.16 3.66A2.25 2.25 0 009.568 3z" />
            <path stroke-linecap="round" stroke-linejoin="round" d="M6 6h.008v.008H6V6z" />
          </svg>
          <div class="flex-1">
            <div class="flex items-center space-x-2">
              <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm">v4.1.17</a>
              <span class="bg-green-100 text-green-800 text-xs font-semibold px-2 py-0.5 rounded-full border border-green-300">Latest</span>
            </div>
            <p class="text-xs text-gray-600 mt-1">last week</p>
          </div>
        </div>
        <a href="#" class="text-sm text-blue-600 hover:underline">+ 295 releases</a>
      </div>
    </div>

    <!-- Sponsor Section -->
    <div class="rounded-md mb-4">
      <div class="px-3 sm:px-4 py-3 border-b border-gray-400">
        <h3 class="font-semibold text-base">Sponsor this project</h3>
      </div>
      <div class="px-3 sm:px-4 py-3">
        <a href="#" class="flex items-center space-x-2 text-blue-600 hover:underline text-sm">
          <svg class="w-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="M13.19 8.688a4.5 4.5 0 011.242 7.244l-4.5 4.5a4.5 4.5 0 01-6.364-6.364l1.757-1.757m13.35-.622l1.757-1.757a4.5 4.5 0 00-6.364-6.364l-4.5 4.5a4.5 4.5 0 001.242 7.244" />
          </svg>
          <span>https://tailwindcss.com/sponsor</span>
        </a>
      </div>
    </div>

    <!-- Packages Section -->
    <div class="rounded-md mb-4">
      <div class="px-3 sm:px-4 py-3 border-b border-gray-400">
        <h3 class="font-semibold text-base">Packages</h3>
      </div>
      <div class="px-3 sm:px-4 py-3">
        <p class="text-sm text-gray-600">No packages published</p>
      </div>
    </div>

    <!-- Used by Section -->
    <div class="rounded-md mb-4">
      <div class="px-3 sm:px-4 py-3 border-b border-gray-400">
        <h3 class="font-semibold text-base">Used by <span class="font-normal text-gray-600">15.2m</span></h3>
      </div>
      <div class="px-3 sm:px-4 py-3">
        <div class="flex items-center">
          <div class="flex -space-x-1">
            <img src="https://avatars.githubusercontent.com/u/4323180?s=64&v=4" alt="" class="w-8 h-8 rounded-full border-2 border-white">
            <img src="https://avatars.githubusercontent.com/u/1834413?s=64&v=4" alt="" class="w-8 h-8 rounded-full border-2 border-white">
            <img src="https://avatars.githubusercontent.com/u/17352934?s=64&v=4" alt="" class="w-8 h-8 rounded-full border-2 border-white">
            <img src="https://avatars.githubusercontent.com/u/12077016?s=64&v=4" alt="" class="w-8 h-8 rounded-full border-2 border-white">
            <img src="https://avatars.githubusercontent.com/u/30317761?s=64&v=4" alt="" class="w-8 h-8 rounded-full border-2 border-white">
            <img src="https://avatars.githubusercontent.com/u/4323180?s=64&v=4" alt="" class="w-8 h-8 rounded-full border-2 border-white">
            <img src="https://avatars.githubusercontent.com/u/1834413?s=64&v=4" alt="" class="w-8 h-8 rounded-full border-2 border-white">
          </div>
          <a href="#" class="ml-3 text-sm text-blue-600 hover:underline whitespace-nowrap">+ 15,233,741</a>
        </div>
      </div>
    </div>

    <!-- Contributors Section -->
    <div class="rounded-md mb-4">
      <div class="px-3 sm:px-4 py-3 border-b border-gray-400 flex items-center justify-between">
        <h3 class="font-semibold text-base">Contributors</h3>
        <span class="bg-gray-200 text-gray-700 text-xs font-semibold px-2 py-1 rounded-full">328</span>
      </div>
      <div class="px-3 sm:px-4 py-3">
        <div class="grid grid-cols-7 gap-1 mb-3">
          <img src="https://avatars.githubusercontent.com/u/4323180?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/1834413?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/17352934?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/12077016?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/30317761?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/4323180?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/1834413?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/17352934?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/12077016?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/30317761?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/4323180?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/1834413?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/17352934?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
          <img src="https://avatars.githubusercontent.com/u/12077016?s=64&v=4" alt="" class="w-8 h-8 rounded-full">
        </div>
        <a href="#" class="text-sm text-blue-600 hover:underline">+ 314 contributors</a>
      </div>
    </div>

    <!-- Languages Section -->
    <div class="rounded-md">
      <div class="px-3 sm:px-4 py-3 border-b border-gray-400">
        <h3 class="font-semibold text-base">Languages</h3>
      </div>
      <div class="px-3 sm:px-4 py-3">
        <!-- Language Bar -->
        <div class="flex w-full h-2 rounded-full overflow-hidden mb-3">
          <div class="bg-blue-600" style="width: 81.3%"></div>
          <div class="bg-orange-400" style="width: 16.2%"></div>
          <div class="bg-gray-400" style="width: 2.5%"></div>
        </div>

        <!-- Language List -->
        <div class="space-y-2">
          <div class="flex items-center justify-between text-sm">
            <div class="flex items-center space-x-2">
              <div class="w-3 h-3 rounded-full bg-blue-600 flex-shrink-0"></div>
              <span class="font-semibold">TypeScript</span>
            </div>
            <span class="text-gray-600">81.3%</span>
          </div>
          <div class="flex items-center justify-between text-sm">
            <div class="flex items-center space-x-2">
              <div class="w-3 h-3 rounded-full bg-orange-400 flex-shrink-0"></div>
              <span class="font-semibold">Rust</span>
            </div>
            <span class="text-gray-600">16.2%</span>
          </div>
          <div class="flex items-center justify-between text-sm">
            <div class="flex items-center space-x-2">
              <div class="w-3 h-3 rounded-full bg-gray-400 flex-shrink-0"></div>
              <span class="font-semibold">Other</span>
            </div>
            <span class="text-gray-600">2.5%</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
