<template>
  <HeaderPage/>
  <HeroSection/>
  <AboutMe/>
</template>

<script>
import HeaderPage from './components/HeaderPage.vue';
import HeroSection from './components/HeroSection.vue'
import AboutMe from './components/AboutMe.vue';

export default {
  name: 'App',
  components: {
    HeaderPage,
    HeroSection,
    AboutMe
  }
}
</script>

<style>
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
