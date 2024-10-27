<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import HeroSection from '@/components/AboutUs/HeroSection.vue'
import StaticsPanel from '@/components/AboutUs/StaticsPanel.vue'
import MissionVision from '@/components/AboutUs/MissionVision.vue'
import BlogSection from '@/components/AboutUs/BlogSection.vue'
import TeamGrid from '@/components/AboutUs/TeamGrid.vue'


</script>

<template>
  <MainLayout>
    <HeroSection>
    </HeroSection>
    <StaticsPanel>
    </StaticsPanel>
    <MissionVision>
    </MissionVision>
    <BlogSection>
    </BlogSection>
    <TeamGrid>
    </TeamGrid>
  </MainLayout>
</template>

<script lang="ts">
import {
  defineComponent
} from 'vue'

export default defineComponent({
  name: 'AboutUsLayout'
})

</script>

<style scoped>

</style>
