<!-- src/components/Home/BlogSection.vue -->
<script lang="ts">
export default {
  name: 'BlogSection'
}
</script>

<template>
  <section class="flex justify-center items-center min-h-[70vh] bg-gray-100 px-8 py-20">
    <div class="w-full max-w-[1400px] text-left">
      <div class="flex gap-12 max-md:flex-col">
        <!-- Text Content Section -->
        <article class="flex flex-col w-[50%] max-md:w-full">
          <div class="flex flex-col self-stretch font-bold text-gray-800">
            <h1 class="text-5xl tracking-tight leading-snug text-gray-900">Why we started this Blog</h1>
            <h2 class="mt-6 text-3xl leading-10 text-gray-700">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.
            </h2>
            <p class="mt-6 text-lg leading-8 text-gray-600">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>
        </article>

        <!-- Image Section -->
        <figure class="w-[50%] max-md:w-full">
          <img
            loading="lazy"
            src="https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/395f138cdfcf52ffb822fbc43cc2080e0d7b514281c46704e661adb2ceaf6294?apiKey=c67971bfdb224af7ac1abd38d94b93d0&"
            alt="Blog illustration showcasing why we started this blog"
            class="object-cover w-full h-auto rounded-lg shadow-lg"
          />
        </figure>
      </div>
    </div>
  </section>
</template>

<style scoped>
/* Optional additional styling */
</style>
