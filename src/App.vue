<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="text-gray-900 text-sm">
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
<div class="repo-stats flex flex-col sm:flex-row items-start sm:items-center justify-between px-4 sm:px-8 py-3 gap-3">
  <div class="flex">
    <div class="flex items-center text-lg sm:text-xl ml-0 sm:ml-2">
      <a href="#" class="text-blue-600 hover:underline font-semibold ml-1">tailwindcss</a>
    </div>
  </div>
  <div class="flex flex-wrap gap-2">
    <div class="flex text-xs">
      <button class="border border-gray-400 rounded rounded-r-none px-2 sm:px-3 py-1 flex items-center space-x-1"><div>Watch</div></button>
      <a class="border border-gray-400 rounded rounded-l-none border-l-none px-2 sm:px-3 py-1 font-semibold hover:text-blue-600">430</a>
    </div>
      <div class="flex text-xs">
      <button class="border border-gray-400 rounded rounded-r-none px-2 sm:px-3 py-1 flex items-center space-x-1"><div>Star</div></button>
      <a class="border border-gray-400 rounded rounded-l-none border-l-none px-2 sm:px-3 py-1 font-semibold hover:text-blue-600">25.2k</a>
    </div>
      <div class="flex text-xs">
      <button class="border border-gray-400 rounded rounded-r-none px-2 sm:px-3 py-1 flex items-center space-x-1"><div>Fork</div></button>
      <a class="border border-gray-400 rounded rounded-l-none border-l-none px-2 sm:px-3 py-1 font-semibold hover:text-blue-600">1.2k</a>
    </div>
  </div>
</div>
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

<div class="container mx-auto my-4 sm:my-9 px-2 sm:px-4 flex flex-col lg:flex-row">
  <div class="flex-explorer-container w-full lg:w-3/4 lg:mr-8">
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

   <!-- Latest Commit Info -->
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

       <!-- Repeat pattern for other files with responsive classes -->
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
           <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">dist</a>
         </div>
         <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Add empty .npmignore so dist files are distributed with releases</a>
           <span class="text-gray-600 whitespace-nowrap">3y</span>
         </div>
       </div>

       <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
         <div class="flex items-center space-x-2 flex-1 min-w-0">
           <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
             <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
           </svg>
           <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">jest</a>
         </div>
         <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Use `process.env.JEST_WORKER_ID`</a>
           <span class="text-gray-600 whitespace-nowrap">15mo</span>
         </div>
       </div>

       <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
         <div class="flex items-center space-x-2 flex-1 min-w-0">
           <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
             <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
           </svg>
           <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">scripts</a>
         </div>
         <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Prevent source maps from being generated</a>
           <span class="text-gray-600 whitespace-nowrap">23d</span>
         </div>
       </div>

       <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
         <div class="flex items-center space-x-2 flex-1 min-w-0">
           <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
             <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
           </svg>
           <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">src</a>
         </div>
         <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Only wrap with variants if rules don't already contain any variants</a>
           <span class="text-gray-600 whitespace-nowrap">6d</span>
         </div>
       </div>

       <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
         <div class="flex items-center space-x-2 flex-1 min-w-0">
           <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
             <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 12.75V12A2.25 2.25 0 014.5 9.75h15A2.25 2.25 0 0121.75 12v.75m-8.69-6.44l-2.12-2.12a1.5 1.5 0 00-1.061-.44H4.5A2.25 2.25 0 002.25 6v12a2.25 2.25 0 002.25 2.25h15A2.25 2.25 0 0021.75 18V9a2.25 2.25 0 00-2.25-2.25h-5.379a1.5 1.5 0 01-1.06-.44z" />
           </svg>
           <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">stubs</a>
         </div>
         <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Generate responsive variants for container by default</a>
           <span class="text-gray-600 whitespace-nowrap">6d</span>
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
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Convert new stuff to use ES6 modules</a>
           <span class="text-gray-600 whitespace-nowrap">3y</span>
         </div>
       </div>

       <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
         <div class="flex items-center space-x-2 flex-1 min-w-0">
           <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
             <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
           </svg>
           <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">.eslintignore</a>
         </div>
         <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Updated CLI init command</a>
           <span class="text-gray-600 whitespace-nowrap">17mo</span>
         </div>
       </div>

       <div class="flex items-center justify-between px-2 sm:px-4 py-2 hover:bg-gray-50">
         <div class="flex items-center space-x-2 flex-1 min-w-0">
           <svg class="w-3 sm:w-4 text-gray-600 flex-shrink-0" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
             <path stroke-linecap="round" stroke-linejoin="round" d="M19.5 14.25v-2.625a3.375 3.375 0 00-3.375-3.375h-1.5A1.125 1.125 0 0113.5 7.125v-1.5a3.375 3.375 0 00-3.375-3.375H8.25m2.25 0H5.625c-.621 0-1.125.504-1.125 1.125v17.25c0 .621.504 1.125 1.125 1.125h12.75c.621 0 1.125-.504 1.125-1.125V11.25a9 9 0 00-9-9z" />
           </svg>
           <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">.eslintrc.json</a>
         </div>
         <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Disable lint rule for TODO comments</a>
           <span class="text-gray-600 whitespace-nowrap">3mo</span>
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
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Fix extension in gitignore</a>
           <span class="text-gray-600 whitespace-nowrap">17mo</span>
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
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Avoid updating license every year</a>
           <span class="text-gray-600 whitespace-nowrap">3y</span>
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
           <a href="#" class="font-semibold hover:text-blue-600 hover:underline text-sm sm:text-base">base.css</a>
         </div>
         <div class="flex items-center space-x-2 sm:space-x-8 text-xs sm:text-sm">
           <a href="#" class="text-gray-600 hover:text-blue-600 hidden lg:block">Remove preflight CSS export in favor of base</a>
           <span class="text-gray-600 whitespace-nowrap">2y</span>
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

  <!-- Sidebar -->
  <div class="sidebar w-full lg:w-1/4 mt-8 lg:mt-0">
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
    <div class="border border-gray-400 rounded-md mb-4">
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
    <div class="border border-gray-400 rounded-md">
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
</div>
  </div>
</template>
