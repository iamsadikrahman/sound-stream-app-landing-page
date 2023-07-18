<template>
  <section>
    <ul>
      <li>
        <a href="">
          <ion-icon name="logo-apple"></ion-icon>
          <span>Free downoad for iPhone</span></a
        >
      </li>
      <li><img src="../assets/images/music.png" alt="divider image" /></li>
      <li>
        <a href="">
          <ion-icon name="logo-android"></ion-icon>
          <span>Free downoad for Android </span></a
        >
      </li>
    </ul>
  </section>
</template>

<script setup></script>

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
