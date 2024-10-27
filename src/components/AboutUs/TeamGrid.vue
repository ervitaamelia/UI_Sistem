<!-- src/components/Team/TeamList.vue -->
<template>
  <section class="flex justify-center items-center min-h-screen bg-gray-100 px-8 py-20">
    <div class="w-full max-w-[1400px] text-center">
      <h4 class="text-6xl font-extrabold tracking-tight leading-tight text-gray-800 max-md:text-5xl">List Of Authors</h4>
      <div class="grid grid-cols-4 gap-8 mt-12 max-md:grid-cols-1">
        <router-link
          v-for="member in teamMembers"
          :key="member.name"
          to="/AuthorView"
          class="flex flex-col hover:shadow-lg transition duration-150 ease-in-out"
        >
          <TeamMember v-bind="member" />
        </router-link>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import TeamMember from './TeamMember.vue';

const teamMembers = [
  {
    name: 'Floyd Miles',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/cbb5b48e8a0e3435ce4903b4895eb803d0ff99360b8dbd5238033ee86b332802?apiKey=c67971bfdb224af7ac1abd38d94b93d0&',
    starsSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/cd2271ccb54a595446c7cf55e8a22617907d2ebda62a1d230817814da94b31c3?apiKey=c67971bfdb224af7ac1abd38d94b93d0&',
  },
  {
    name: 'Dianne Russell',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/df167acd41ee793d00ba35e2ce34c50c5f652c16adcdf7949de617bea0c833ca?apiKey=c67971bfdb224af7ac1abd38d94b93d0&',
    starsSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/02451378c712d3e68163af60cdc94a486e9cdf509ea02c1059d02809304bcf9f?apiKey=c67971bfdb224af7ac1abd38d94b93d0&',
    highlighted: true,
  },
  {
    name: 'Dianne Russell',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/df167acd41ee793d00ba35e2ce34c50c5f652c16adcdf7949de617bea0c833ca?apiKey=c67971bfdb224af7ac1abd38d94b93d0&',
    starsSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/02451378c712d3e68163af60cdc94a486e9cdf509ea02c1059d02809304bcf9f?apiKey=c67971bfdb224af7ac1abd38d94b93d0&',
    highlighted: true,
  },
  {
    name: 'Dianne Russell',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/df167acd41ee793d00ba35e2ce34c50c5f652c16adcdf7949de617bea0c833ca?apiKey=c67971bfdb224af7ac1abd38d94b93d0&',
    starsSrc: 'https://cdn.builder.io/api/v1/image/assets/c67971bfdb224af7ac1abd38d94b93d0/02451378c712d3e68163af60cdc94a486e9cdf509ea02c1059d02809304bcf9f?apiKey=c67971bfdb224af7ac1abd38d94b93d0&',
    highlighted: true,
  },
  // Tambahkan lebih banyak anggota tim di sini...
];
</script>

<style scoped>
/* Tambahkan gaya tambahan di sini jika diperlukan */
</style>
