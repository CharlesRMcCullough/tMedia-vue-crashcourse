<script setup>
  import NavbarHead from './components/NavBar.vue';
  import HeroBody from './components/HeroBody.vue';
  import HomeCards from './components/CardHome.vue';
  import JobListings from './components/JobListings.vue';
</script>

<template>
  <NavbarHead />
  <HeroBody />
  <HomeCards />
  <JobListings :limit="3" :show-button="true" />
</template>

<style scoped>

</style>
