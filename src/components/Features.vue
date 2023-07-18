<template>
  <section>
    <ul>
      <li>
        <h3>{{ features[0].name }}</h3>
        <p>{{ features[0].desc }}</p>
      </li>
      <li>
        <h3>{{ features[1].name }}</h3>
        <p>{{ features[1].desc }}</p>
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
        <h3>{{ features[2].name }}</h3>
        <p>{{ features[2].desc }}</p>
      </li>
      <li>
        <h3>{{ features[3].name }}</h3>
        <p>{{ features[3].desc }}</p>
      </li>
    </ul>
  </section>
</template>

<script setup>
const features = [
  {
    name: "Apple AirPlay",
    desc:
      "Each time a digital asset is purchased or sold, Sequoir is donates a percentage",
  },
  {
    name: "SONOS Wireless HiFi",
    desc:
      "Each time a digital asset is purchased or sold, Sequoir is donates a percentage",
  },
  {
    name: "Samsung Multiroom",
    desc:
      "Each time a digital asset is purchased or sold, Sequoir is donates a percentage",
  },
  {
    name: "Strategy & Design",
    desc:
      "Each time a digital asset is purchased or sold, Sequoir is donates a percentage",
  },
];
</script>

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
