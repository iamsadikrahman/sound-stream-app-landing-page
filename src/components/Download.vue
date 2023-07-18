<template>
  <section>
    <ul>
      <li>
        <a href="">
          <ion-icon name="logo-apple" :style="iphoneCOlor"></ion-icon>
          <span>Free downoad for iPhone</span></a
        >
      </li>
      <li><img src="../assets/images/music.png" alt="divider image" /></li>
      <li>
        <a href="">
          <ion-icon name="logo-android" :style="androidColor"></ion-icon>
          <span>Free downoad for Android </span></a
        >
      </li>
    </ul>
  </section>
</template>

<script setup>
const iphoneCOlor = "color: rgb(184, 172, 172)";
const androidColor = "color: rgb(75, 228, 126)";
</script>

<style scoped>
ul {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 5rem;
}

li a {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

ion-icon {
  font-size: 4.5rem;
}

span {
  font-size: 1.5rem;
  width: 65%;
  text-align: center;
}
</style>
