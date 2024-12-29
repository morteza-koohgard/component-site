<template>
  <div class="w-full flex justify-center min-h-screen">
    <div class="w-full max-w-7xl">
      <header class="bg-gray-100 flex justify-between items-center px-6 py-4 border-b">
        <!-- Logo -->
        <div class="flex items-center">
          <NuxtLink to="/" class="text-xl font-bold">
            YourLogo
          </NuxtLink>
        </div>

        <!-- Navigation Links -->
        <nav class="flex items-center gap-6">
          <a href="https://github.com/yourusername" target="_blank" rel="noopener noreferrer"
            class="text-gray-600 hover:text-gray-900 transition-colors"
          >
            GitHub
          </a>
          <a href="https://youtube.com/@yourchannel" target="_blank" rel="noopener noreferrer"
            class="text-gray-600 hover:text-gray-900 transition-colors"
          >
            YouTube
          </a>
          <a href="/feedback" class="text-gray-600 hover:text-gray-900 transition-colors">
            Feedback
          </a>
        </nav>
      </header>
      
      <slot />
    </div>
  </div>
</template>

<script setup lang="ts">
</script>
