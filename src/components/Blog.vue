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
            <h3>See How People Are Using Your Website With Hotjar</h3>
            <p>
              Each time a digital asset is purchased or sold, Sequoir donates a percentage
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
            <h3>5 Tips to Write Your Own Website Copy</h3>
            <p>
              Each time a digital asset is purchased or sold, Sequoir donates a percentage
            </p>
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
            <h3>5 Brilliant Apps That Will Make Your Life Better</h3>
            <p>
              Each time a digital asset is purchased or sold, Sequoir donates a percentage
            </p>
          </div>
        </a>
      </li>
    </ul>
  </section>
</template>

<script setup></script>

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
