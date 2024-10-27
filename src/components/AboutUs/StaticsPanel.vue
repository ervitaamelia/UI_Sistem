<!-- src/components/Statistics/StatisticsPanel.vue -->
<script lang="ts">
export default {
  name: 'StatisticsPanel'
}
</script>

<template>
  <section class="flex justify-center items-center min-h-[60vh] bg-gray-100">
    <div class="w-full max-w-[1200px] text-center">
      <div class="px-16 py-12 max-w-full bg-blue-600 rounded-lg shadow-lg">
        <div class="flex gap-8 max-md:flex-col">
          <article class="flex flex-col w-[30%]">
            <div class="flex flex-col grow text-white">
              <h2 class="self-start text-7xl font-extrabold tracking-tight leading-none">12+</h2>
              <p class="text-lg leading-8 mt-2">Blogs Published</p>
            </div>
          </article>
          <article class="flex flex-col w-[30%]">
            <div class="flex flex-col grow text-white">
              <h2 class="self-start text-7xl font-extrabold tracking-tight leading-none">18K+</h2>
              <p class="text-lg leading-8 mt-2">Views on Finsweet</p>
            </div>
          </article>
          <article class="flex flex-col w-[30%]">
            <div class="flex flex-col grow text-white">
              <h2 class="self-start text-7xl font-extrabold tracking-tight leading-none">30K+</h2>
              <p class="text-lg leading-8 mt-2">Total Active Users</p>
            </div>
          </article>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* Optional additional styling */
</style>
