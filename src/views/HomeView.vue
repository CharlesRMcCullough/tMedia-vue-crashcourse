<script setup>
import HeroBody from '@/components/HeroBody.vue'
import HomeCards from '@/components/CardHome.vue'
import JobListings from '@/components/JobListings.vue'
</script>

<template>
    <HeroBody />
    <HomeCards />
    <JobListings :limit="3" :show-button="true" />
</template>
