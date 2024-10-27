<template>
  <main class="flex flex-col px-20 mt-16 w-full max-md:px-5 max-md:mt-10 max-md:max-w-full">
    <header>
      <h1 class="self-start text-5xl font-bold tracking-tighter leading-none text-gray-800 max-md:text-4xl">
        All posts
      </h1>
      <hr class="shrink-0 mt-8 h-px border border-solid bg-zinc-500 border-zinc-500 opacity-[0.32] max-md:max-w-full" />
    </header>

    <section class="mt-16 w-full max-w-[1147px] max-md:mt-10 max-md:max-w-full">
      <div class="flex gap-5 max-md:flex-col">
        <aside class="flex flex-col w-[44%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col grow max-md:mt-8 max-md:max-w-full">
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/dafc832692f064b1e9cede46d64fbd4e375a21b3a6424516083c63b2bfa3e204?apiKey=c67971bfdb224af7ac1abd38d94b93d0&" alt="Design tips article featured image" class="object-contain w-full aspect-[1.54] max-md:max-w-full" />
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/6a6ea48ae522c3bc971402c03dc63d0cb1b536800beb648e1f0e91b082b63464?apiKey=c67971bfdb224af7ac1abd38d94b93d0&" alt="Web design clients article featured image" class="object-contain mt-16 w-full aspect-[1.54] max-md:mt-10 max-md:max-w-full" />
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/4abc41bd57d332af1d45d35539eb441fb43718ab1e3a6f58246a80a357f5bfe0?apiKey=c67971bfdb224af7ac1abd38d94b93d0&" alt="Logo design trends article featured image" class="object-contain mt-16 w-full aspect-[1.54] max-md:mt-10 max-md:max-w-full" />
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/a31a4ef91fce621e30583ae54aa725b36189090048c6493b3ada6dc32544d50e?apiKey=c67971bfdb224af7ac1abd38d94b93d0&" alt="Figma design systems article featured image" class="object-contain mt-16 w-full aspect-[1.54] max-md:mt-10 max-md:max-w-full" />
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/dafc832692f064b1e9cede46d64fbd4e375a21b3a6424516083c63b2bfa3e204?apiKey=c67971bfdb224af7ac1abd38d94b93d0&" alt="Font sizes article featured image" class="object-contain mt-16 w-full aspect-[1.54] max-md:mt-10 max-md:max-w-full" />
          </div>
        </aside>

        <article class="flex flex-col ml-5 w-[56%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col self-stretch my-auto text-base font-semibold leading-none text-amber-300 max-md:mt-10 max-md:max-w-full">
            <BlogPostSection
              category="Startup"
              title="Design tips for designers that cover everything you need"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />

            <BlogPostSection
              category="Business"
              title="How to build rapport with your web design clients"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />

            <BlogPostSection
              category="Startup"
              title="Logo design trends to avoid in 2022"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />

            <BlogPostSection
              category="Technology"
              title="8 Figma design systems you can download for free today"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />

            <BlogPostSection
              category="Economy"
              title="Font sizes in UI design: The complete guide to follow"
              description="Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident."
            />
          </div>
        </article>
      </div>
    </section>

    <nav class="flex gap-4 self-center mt-16 ml-3.5 max-w-full font-bold text-center w-[174px] max-md:mt-10">
      <button class="grow my-auto text-2xl leading-none text-zinc-500" aria-label="Previous page">
        &lt; Prev
      </button>
      <button class="text-3xl tracking-tighter leading-none text-gray-800" aria-label="Next page">
        Next &gt;
      </button>
    </nav>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import BlogPostSection from './BlogPostSection.vue'

export default defineComponent({
  name: 'BlogPosts',
  components: {
    BlogPostSection
  }
})
</script>
