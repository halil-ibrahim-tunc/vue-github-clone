<script setup lang="ts">
</script>

<template>
  <nav class="bg-gray-900 text-white px-2 sm:px-4 py-3 flex items-center justify-between">
    <div class="flex items-center space-x-2 sm:space-x-4">
      <a href="#" class="text-white hover:text-gray-400">
        <svg class="w-6 sm:w-8 fill-current" height="32" aria-hidden="true" viewBox="0 0 24 24" version="1.1" width="32"
          data-view-component="true">
          <path
            d="M12 1C5.923 1 1 5.923 1 12c0 4.867 3.149 8.979 7.521 10.436.55.096.756-.233.756-.522 0-.262-.013-1.128-.013-2.049-2.764.509-3.479-.674-3.699-1.292-.124-.317-.66-1.293-1.127-1.554-.385-.207-.936-.715-.014-.729.866-.014 1.485.797 1.691 1.128.99 1.663 2.571 1.196 3.204.907.096-.715.385-1.196.701-1.471-2.448-.275-5.005-1.224-5.005-5.432 0-1.196.426-2.186 1.128-2.956-.111-.275-.496-1.402.11-2.915 0 0 .921-.288 3.024 1.128a10.193 10.193 0 0 1 2.75-.371c.936 0 1.871.123 2.75.371 2.104-1.43 3.025-1.128 3.025-1.128.605 1.513.221 2.64.111 2.915.701.77 1.127 1.747 1.127 2.956 0 4.222-2.571 5.157-5.019 5.432.399.344.743 1.004.743 2.035 0 1.471-.014 2.654-.014 3.025 0 .289.206.632.756.522C19.851 20.979 23 16.854 23 12c0-6.077-4.922-11-11-11Z">
          </path>
        </svg>
      </a>
      <div class="relative hidden md:block">
        <input type="text" class="rounded bg-gray-700 placeholcer-white w-40 lg:w-72 px-3 py-1"
          placeholder="Search or jump to..." />
        <div class="absolute top-0 right-0 flex items-center h-full">
          <div class="border border-gray-600 rounded text-sm text-gray-400 px-2 mr-2">/</div>
        </div>
      </div>
      <ul class="hidden lg:flex items-center font-semibold space-x-4">
        <li>
          <a href="#" class="hover:text-gray-400"> Pull Requests</a>
        </li>
        <li> <a href="#" class="hover:text-gray-400"> Issues</a></li>
        <li> <a href="#" class="hover:text-gray-400"> Marketplace</a></li>
        <li> <a href="#" class="hover:text-gray-400">Explore</a></li>
      </ul>
    </div>
    <div class="flex items-center space-x-2 sm:space-x-4 text-white">
      <a href="#" class="relative hover:text-gray-400 hidden sm:block">
        <svg class="w-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
          stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round"
            d="M14.857 17.082a23.848 23.848 0 0 0 5.454-1.31A8.967 8.967 0 0 1 18 9.75V9A6 6 0 0 0 6 9v.75a8.967 8.967 0 0 1-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 0 1-5.714 0m5.714 0a3 3 0 1 1-5.714 0" />
        </svg>
        <div class="bg-blue-600 rounded-full w-2 h-2 absolute top-0 right-0"></div>
      </a>
      <a href="#" class="flex items-center hover:text-gray-400 hidden sm:flex">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
          stroke="currentColor" class="size-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
        </svg>
        <svg class="w-3" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
          stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
        </svg>
      </a>
      <a href="#" class="flex items-center hover:text-gray-400">
        <img src="https://avatars.githubusercontent.com/u/224747121?v=4" alt="" size="32" height="32" width="32"
          data-view-component="true" class="w-5 h-5 rounded-full">
        <svg class="w-3" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
          stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
        </svg>
      </a>
    </div>
  </nav>
</template>
