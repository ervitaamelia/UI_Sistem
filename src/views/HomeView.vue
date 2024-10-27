<template>
  <MainLayout>
    <HeroSection />
    <FeaturedPosts />
    <AboutSection />
    <CategorySection />
  </MainLayout>
</template>

<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue';
import HeroSection from '@/components/Home/HeroSection.vue';
import FeaturedPosts from '@/components/Home/FeaturedPost.vue';
import AboutSection from '@/components/Home/AboutSection.vue';
import CategorySection from '@/components/Home/CategorySection.vue';
</script>
