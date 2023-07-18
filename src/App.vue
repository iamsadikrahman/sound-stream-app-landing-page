<template>
  <header>
    <Navbar />
    <Hero />
  </header>
  <Download />
  <Features />
  <Overview />
  <Blog />
  <footer>
    <Footer />
  </footer>
</template>

<script setup>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";
import Download from "./components/Download.vue";
import Features from "./components/Features.vue";
import Overview from "./components/Overview.vue";
import Blog from "./components/Blog.vue";
import Footer from "./components/Footer.vue";
</script>

<style scoped>
header {
  min-height: 100vh;
}
</style>
