<script setup lang="ts">
import GitHubNavbar from './components/GitHubNavbar.vue'
import RepositoryHeader from './components/RepositoryHeader.vue'
import FileExplorer from './components/FileExplorer.vue'
import RepositorySidebar from './components/RepositorySidebar.vue'
</script>

<template>
  <div class="text-gray-900 text-sm">
    <GitHubNavbar />
    <RepositoryHeader />

    <div class="container mx-auto my-4 sm:my-9 px-2 sm:px-4 flex flex-col lg:flex-row">
      <FileExplorer />
      <RepositorySidebar />
    </div>
  </div>
</template>
