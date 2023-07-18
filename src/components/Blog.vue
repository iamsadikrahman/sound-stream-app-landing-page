<template>
  <section>
    <h2>Latest Blog & Stories</h2>
    <ul>
      <li>
        <a href="">
          <figure>
            <img
              src="../assets/images/blog-1.jpg"
              alt="See How People Are Using Your Website With Hotjar"
            />
            <time datetime="">05 Fab, 2022</time>
          </figure>
          <div>
            <h3>{{ posts[0].title }}</h3>
            <p>
              {{ posts[0].summary }}
            </p>
          </div>
        </a>
      </li>
      <li>
        <a href="">
          <figure>
            <img
              src="../assets/images/blog-2.jpg"
              alt="5 Tips to Write Your Own Website Copy"
            />
            <time datetime="">06 Fab, 2022</time>
          </figure>
          <div>
            <h3>{{ posts[1].title }}</h3>
            <p>{{ posts[1].summary }}</p>
          </div>
        </a>
      </li>
      <li>
        <a href="">
          <figure>
            <img
              src="../assets/images/blog-3.jpg"
              alt="5 Brilliant Apps That Will Make Your Life Better"
            />
            <time datetime="">10 Fab, 2022</time>
          </figure>
          <div>
            <h3>{{ posts[2].title }}</h3>
            <p>{{ posts[2].summary }}</p>
          </div>
        </a>
      </li>
    </ul>
  </section>
</template>

<script setup>
const posts = [
  {
    title: "See How People Are Using Your Website With Hotjar",

    summary:
      "Each time a digital asset is purchased or sold, Sequoir donates a percentage",
  },
  {
    title: "5 Tips to Write Your Own Website Copy",

    summary:
      "Each time a digital asset is purchased or sold, Sequoir donates a percentage",
  },
  {
    title: "5 Brilliant Apps That Will Make Your Life Better",

    summary:
      "Each time a digital asset is purchased or sold, Sequoir donates a percentage",
  },
];
</script>

<style scoped>
ul {
  display: flex;
  padding: 0;
  gap: 2rem;
}

ul li a {
  display: flex;
  flex-direction: column;
}

figure {
  margin: 0;
}

time {
  position: relative;
  bottom: 1rem;
  left: 30%;
  background-color: wheat;
  padding: 0.4rem 0.5rem;
  border-radius: 0.5rem;
}
</style>
