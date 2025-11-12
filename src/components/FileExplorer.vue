<script setup lang="ts">
</script>

<template>
  <div class="flex-explorer-container w-full lg:w-3/4 lg:mr-8">
    <!-- Branch Navigation -->
    <div class="branch-navigation flex flex-col sm:flex-row items-start sm:items-center justify-between gap-3">
      <div class="flex items-center flex-wrap gap-1">
        <button class="border border-gray-400 rounded-md px-2 sm:px-4 py-1 hover:bg-gray-200 flex items-center space-x-1 sm:space-x-2 text-xs sm:text-sm">
          <svg class="w-3 sm:w-4 hidden sm:block" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 7.5l3 2.25-3 2.25m4.5 0h3m-9 8.25h13.5A2.25 2.25 0 0021 18V6a2.25 2.25 0 00-2.25-2.25H5.25A2.25 2.25 0 003 6v12a2.25 2.25 0 002.25 2.25z" />
          </svg>
          <div>master</div>
          <svg class="w-3" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
          </svg>
        </button>
        <a href="#" class="flex items-center space-x-1 sm:space-x-2 px-2 sm:px-3 py-1 group text-xs sm:text-sm">
          <svg class="w-3 sm:w-4 text-gray-600 hidden sm:block" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="M7.5 21L3 16.5m0 0L7.5 12M3 16.5h13.5m0-13.5L21 7.5m0 0L16.5 12M21 7.5H7.5" />
          </svg>
          <span class="text-gray-600 group-hover:text-blue-600">
            <span class="font-semibold">25</span>
            <span class="hidden sm:inline">branches</span>
          </span>
        </a>
        <a href="#" class="flex items-center space-x-1 sm:space-x-2 px-2 sm:px-3 py-1 group text-xs sm:text-sm">
          <svg class="w-3 sm:w-4 text-gray-600 hidden sm:block" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="M9.568 3H5.25A2.25 2.25 0 003 5.25v4.318c0 .597.237 1.17.659 1.591l9.581 9.581c.699.699 1.78.872 2.607.33a18.095 18.095 0 005.223-5.223c.542-.827.369-1.908-.33-2.607L11.16 3.66A2.25 2.25 0 009.568 3z" />
            <path stroke-linecap="round" stroke-linejoin="round" d="M6 6h.008v.008H6V6z" />
          </svg>
          <span class="text-gray-600 group-hover:text-blue-600">
            <span class="font-semibold">79</span>
            <span class="hidden sm:inline">tags</span>
          </span>
        </a>
      </div>
      <div class="flex items-center space-x-1 sm:space-x-2 w-full sm:w-auto">
        <button class="border border-gray-400 rounded-md px-2 sm:px-3 py-1 text-xs hover:bg-gray-200 flex items-center space-x-1 hidden sm:flex">
          <span>Go to file</span>
        </button>
        <button class="border border-gray-400 rounded-md px-2 sm:px-3 py-1 text-xs hover:bg-gray-200 flex items-center space-x-1 hidden sm:flex">
          <span>Add file</span>
          <svg class="w-3" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
          </svg>
        </button>
        <button class="bg-green-600 text-white rounded-md px-2 sm:px-3 py-1 text-xs hover:bg-green-700 flex items-center space-x-1 flex-1 sm:flex-none justify-center">
          <svg class="w-3 sm:w-4 hidden sm:block" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="M17.25 6.75L22.5 12l-5.25 5.25m-10.5 0L1.5 12l5.25-5.25m7.5-3l-4.5 16.5" />
          </svg>
          <span>Code</span>
          <svg class="w-3" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
          </svg>
        </button>
      </div>
    </div>

    <!-- Latest Commit Info & File List -->
    <div class="border border-gray-400 rounded-md mt-4">
      <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between px-3 sm:px-4 py-2 bg-gray-100 border-b border-gray-400 gap-2">
        <div class="flex items-center space-x-2">
          <img src="https://avatars.githubusercontent.com/u/4323180?s=48&v=4" alt="" class="w-5 h-5 sm:w-6 sm:h-6 rounded-full">
          <a href="#" class="font-semibold hover:underline text-sm sm:text-base">adamwathan</a>
          <a href="#" class="text-gray-600 hover:text-blue-600 hover:underline text-xs sm:text-sm">1.5.1</a>
        </div>
        <div class="flex items-center space-x-2 sm:space-x-4 text-xs sm:text-sm w-full sm:w-auto justify-between sm:justify-end">
          <a href="#" class="flex items-center space-x-1 text-gray-600 hover:text-blue-600">
            <svg class="w-3 sm:w-4 hidden sm:block" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
            <span class="font-semibold">da070bd</span>
          </a>
          <span class="text-gray-600">6 days ago</span>
          <a href="#" class="flex items-center space-x-1 text-gray-600 hover:text-blue-600 hidden sm:flex">
            <svg class="w-4" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
            <span class="font-semibold">3,040</span>
            <span>commits</span>
          </a>
        </div>
      </div>

      <!-- File Explorer -->
      <div class="divide-y divide-gray-300">
        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base truncate">.github</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block truncate max-w-xs">Update issue templates</a>
            <span class="text-gray-600 whitespace-nowrap">13d</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">__tests__</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Remove stale test</a>
            <span class="text-gray-600 whitespace-nowrap">6d</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base truncate">dist</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block truncate max-w-xs">Build production assets</a>
            <span class="text-gray-600 whitespace-nowrap">6d</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base truncate">node_modules</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block truncate max-w-xs">Update dependencies</a>
            <span class="text-gray-600 whitespace-nowrap">2w</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base truncate">public</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block truncate max-w-xs">Add favicon</a>
            <span class="text-gray-600 whitespace-nowrap">1mo</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base truncate">src</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block truncate max-w-xs">Refactor component structure</a>
            <span class="text-gray-600 whitespace-nowrap">3d</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">.editorconfig</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Add editor configuration</a>
            <span class="text-gray-600 whitespace-nowrap">3mo</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">.eslintrc.cjs</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Update ESLint rules</a>
            <span class="text-gray-600 whitespace-nowrap">1w</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">.gitignore</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Ignore IDE files</a>
            <span class="text-gray-600 whitespace-nowrap">2mo</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">.prettierrc.json</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Configure Prettier</a>
            <span class="text-gray-600 whitespace-nowrap">3mo</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">CHANGELOG.md</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Update changelog for v1.5.1</a>
            <span class="text-gray-600 whitespace-nowrap">6d</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">LICENSE</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Update copyright year</a>
            <span class="text-gray-600 whitespace-nowrap">4mo</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">package.json</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Bump version to 1.5.1</a>
            <span class="text-gray-600 whitespace-nowrap">6d</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">README.md</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Add alt attribute to logo</a>
            <span class="text-gray-600 whitespace-nowrap">2mo</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">tailwind.config.js</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Add custom color palette</a>
            <span class="text-gray-600 whitespace-nowrap">1w</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">tsconfig.json</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Update TypeScript config</a>
            <span class="text-gray-600 whitespace-nowrap">2w</span>
          </div>
        </div>

        <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
          <div class="flex items-center space-x-2 flex-1 min-w-0">
            <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">vite.config.ts</a>
          </div>
          <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
            <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Configure build optimization</a>
            <span class="text-gray-600 whitespace-nowrap">1w</span>
          </div>
        </div>
      </div>
    </div>

    <!-- README Section -->
    <div class="mt-8">
      <div class="border border-gray-400 rounded-md">
        <div class="flex items-center justify-between px-4 py-2 bg-gray-100 border-b border-gray-400">
          <div class="flex items-center space-x-2">
            <svg class="w-4 text-gray-600" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
            </svg>
            <span class="font-semibold">README.md</span>
          </div>
        </div>
        <div class="px-4 py-6">
          <div class="text-center mb-6">
            <img src="https://raw.githubusercontent.com/tailwindlabs/tailwindcss/master/.github/logo-light.svg" alt="Tailwind CSS" class="h-16 mx-auto">
          </div>
          <p class="text-gray-700 text-center mb-4">
            A utility-first CSS framework for rapidly building custom user interfaces.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
