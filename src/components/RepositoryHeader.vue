<script setup lang="ts">
</script>

<template>
  <div>
    <!-- Repository Stats -->
    <div class="repo-stats flex flex-col sm:flex-row items-start sm:items-center justify-between px-4 sm:px-8 py-3 gap-3">
      <div class="flex">
        <div class="flex items-center text-lg sm:text-xl ml-0 sm:ml-2">
          <a href="#" class="text-blue-600 hover:underline font-semibold ml-1">tailwindcss</a>
        </div>
      </div>
      <div class="flex flex-wrap gap-2">
        <div class="flex text-xs">
          <button class="border border-gray-400 rounded rounded-r-none px-2 sm:px-3 py-1 flex items-center space-x-1">
            <div>Watch</div>
          </button>
          <a class="border border-gray-400 rounded rounded-l-none border-l-none px-2 sm:px-3 py-1 font-semibold hover:text-blue-600">430</a>
        </div>
        <div class="flex text-xs">
          <button class="border border-gray-400 rounded rounded-r-none px-2 sm:px-3 py-1 flex items-center space-x-1">
            <div>Star</div>
          </button>
          <a class="border border-gray-400 rounded rounded-l-none border-l-none px-2 sm:px-3 py-1 font-semibold hover:text-blue-600">25.2k</a>
        </div>
        <div class="flex text-xs">
          <button class="border border-gray-400 rounded rounded-r-none px-2 sm:px-3 py-1 flex items-center space-x-1">
            <div>Fork</div>
          </button>
          <a class="border border-gray-400 rounded rounded-l-none border-l-none px-2 sm:px-3 py-1 font-semibold hover:text-blue-600">1.2k</a>
        </div>
      </div>
    </div>

    <!-- Repository Navigation Tabs -->
    <ul class="repo-nav border-b border-gray-400 flex items-center px-4 sm:px-8 mt-4 overflow-x-auto">
      <li class="font-semibold flex-shrink-0">
        <a href="#" class="flex items-center border-b-2 border-b-red-500 border-transparent hover:border-gray-400 transition ease-iniout duration-150 px-2 sm:px-4 p-3">
          <span>Code</span>
        </a>
      </li>
      <li class="flex-shrink-0">
        <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-iniout duration-150 px-2 sm:px-4 p-3">
          <span>Issues</span>
        </a>
      </li>
      <li class="hidden sm:block flex-shrink-0">
        <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-iniout duration-150 px-2 sm:px-4 p-3">
          <span>Pull Requests</span>
        </a>
      </li>
      <li class="hidden md:block flex-shrink-0">
        <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-iniout duration-150 px-2 sm:px-4 p-3">
          <span>Discussions</span>
        </a>
      </li>
      <li class="hidden md:block flex-shrink-0">
        <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-iniout duration-150 px-2 sm:px-4 p-3">
          <span>Actions</span>
        </a>
      </li>
      <li class="hidden lg:block flex-shrink-0">
        <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-iniout duration-150 px-2 sm:px-4 p-3">
          <span>Security</span>
        </a>
      </li>
      <li class="hidden lg:block flex-shrink-0">
        <a href="#" class="flex items-center border-b-2 border-transparent hover:border-gray-400 transition ease-iniout duration-150 px-2 sm:px-4 p-3">
          <span>Insights</span>
        </a>
      </li>
    </ul>
  </div>
</template>
