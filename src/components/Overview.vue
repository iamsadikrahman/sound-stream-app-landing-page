<template>
  <section>
    <figure>
      <img src="../assets/images/overview-banner.png" alt="overview banner" />
    </figure>
    <div>
      <h2>Enjoy your music everywhere!</h2>
      <p>
        Each time a digital asset is purchased or sold, Sequoir donates a percentage of
        the fees back into the development
      </p>
      <ul>
        <li>
          <ion-icon name="wifi"></ion-icon>
          <span>Works exactly like original <strong>Apple AirPlay</strong> </span>
        </li>
        <li>
          <ion-icon name="musical-notes"></ion-icon>
          <span
            ><strong>AirAudio recognizes</strong> if you are listening to your music
          </span>
        </li>
        <li>
          <ion-icon name="star"></ion-icon>
          <span><strong>Create shortcuts</strong> for your favorite receivers </span>
        </li>
      </ul>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
section {
  display: flex;
  align-items: center;
  background-color: #04000f;
  border-radius: 1rem;
}

figure img {
  width: 100%;
}

div {
  display: flex;
  flex-direction: column;
}

h2 {
  font-size: 2rem;
}
p {
  font-size: 1.1rem;
}

ul {
  padding: 0rem;
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}

li span {
  padding-left: 0.5rem;
}

ion-icon {
  color: #da3453;
}
</style>
