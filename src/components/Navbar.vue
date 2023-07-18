<template>
  <nav>
    <h2>Sound Stream</h2>
    <ul>
      <li>
        <a href="#">{{ navItems[0] }}</a>
      </li>
      <li>
        <a href="">{{ navItems[1] }}</a>
      </li>
      <li>
        <a href="">{{ navItems[2] }}</a>
      </li>
      <li>
        <a href="">{{ navItems[3] }}</a>
      </li>
      <li>
        <a href="">{{ navItems[4] }}</a>
      </li>
      <li>
        <a href="">{{ navItems[5] }}</a>
      </li>
      <li>
        <button>
          <a :href="getStartedUrl">{{ navItems[6] }}</a>
        </button>
      </li>
    </ul>
  </nav>
</template>

<script setup>
const navItems = [
  "Home",
  "Features",
  "Overview",
  "Blog",
  "Pricing",
  "FAQ's",
  "Get started",
];

const getStartedUrl = "https://google.com";
</script>

<style scoped>
nav,
nav ul {
  display: flex;
  justify-content: space-between;
}

ul {
  gap: 2rem;
  align-items: center;
}
</style>
