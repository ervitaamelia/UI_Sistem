<script setup lang="ts">
import CategoryCard from './CategoryCard.vue';

const categories = [
  {
    title: 'Business',
    description: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit.',
    iconSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/1f6caa464f89441947adf7010f508de88e396385dc4e183a16249f0d3d4ce590?apiKey=c67971bfdb224af7ac1abd38d94b93d0&'
  },
  {
    title: 'Startup',
    description: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit.',
    iconSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/2541bc3459cf00b591db109ef9bebc1f77898eb8598624242b2e00eb09b89183?apiKey=c67971bfdb224af7ac1abd38d94b93d0&',
    isHighlighted: true
  },
  {
    title: 'Economy',
    description: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit.',
    iconSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/5493c471e715d7eacf17e7047e68a050f5b3cb0ab9fe9a9147c0199fdb0f36b7?apiKey=c67971bfdb224af7ac1abd38d94b93d0&'
  },
  {
    title: 'Technology',
    description: 'Lorem ipsum dolor sit amet, consectetuer adipiscing elit.',
    iconSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/f0317f360fc6b7451c80aabf16648201c0aad1405b64903ced4a998fefd6026d?apiKey=c67971bfdb224af7ac1abd38d94b93d0&'
  }
];
</script>

<template>
  <section class="flex flex-col items-center px-20 mt-16 w-full max-md:px-5 max-md:mt-10 max-md:max-w-full">
    <h2 class="self-start text-4xl font-bold tracking-tighter leading-none text-gray-800">
      All Categories
    </h2>
    <div class="self-stretch mt-12 max-md:mt-10 max-md:max-w-full">
      <div class="flex gap-5 max-md:flex-col">
        <CategoryCard
          v-for="category in categories"
          :key="category.title"
          v-bind="category"
        />
      </div>
    </div>
  </section>
</template>
