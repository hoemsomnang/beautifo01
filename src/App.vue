<script setup>
import { RouterView } from 'vue-router'
import AnnouncementBar from './components/AnnouncementBar.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <AnnouncementBar />
  <Header />
  <RouterView />
  <Footer />
</template>

<style scoped>
</style>
