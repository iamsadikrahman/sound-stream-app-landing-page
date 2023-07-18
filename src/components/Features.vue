<template>
  <section>
    <ul>
      <li>
        <h3>Apple AirPlay</h3>
        <p>
          Each time a digital asset is purchased or sold, Sequoir is donates a percentage
        </p>
      </li>
      <li>
        <h3>SONOS Wireless HiFi</h3>
        <p>
          Each time a digital asset is purchased or sold, Sequoir is donates a percentage
        </p>
      </li>
    </ul>
    <figure>
      <img
        class="features-image-bg"
        src="../assets/images/feature-banner-bg.png"
        alt="circle audio waveform"
      />
      <img
        class="features-image"
        src="../assets/images/feature-banner.png"
        alt="sound stream app"
      />
    </figure>
    <ul>
      <li>
        <h3>Samsung Multiroom</h3>
        <p>
          Each time a digital asset is purchased or sold, Sequoir is donates a percentage
        </p>
      </li>
      <li>
        <h3>Strategy & Design</h3>
        <p>
          Each time a digital asset is purchased or sold, Sequoir is donates a percentage
        </p>
      </li>
    </ul>
  </section>
</template>

<script setup></script>

<style scoped>
section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 5rem;
}

li {
  display: flex;
  flex-direction: column;
}

.features-image-bg {
  position: absolute;
  transform: translateX(calc(-25%));
}

.features-image {
  position: relative;
  bottom: 1.2rem;
}
</style>
