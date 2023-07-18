<template>
  <section>
    <div class="social-follow">
      <a href="#"><h2>Sound Stream</h2></a>
      <p>Follow us on</p>
      <ul class="social-icons">
        <li>
          <a href="#">
            <ion-icon name="logo-youtube"></ion-icon>
          </a>
        </li>
        <li>
          <a href="#"><ion-icon name="logo-github"></ion-icon></a>
        </li>
        <li>
          <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
        </li>
        <li>
          <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
        </li>
      </ul>
    </div>
    <div class="footer-list">
      <ul>
        <li><h3>Company</h3></li>
        <li><a href="#">About Us </a></li>
        <li><a href="#">Features</a></li>
        <li><a href="#">Pricing</a></li>
      </ul>
      <ul>
        <li><h3>Products</h3></li>
        <li><a href="#">Blog</a></li>
        <li><a href="#">Help Center </a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <ul>
        <li><h3>Resources</h3></li>
        <li><a href="#">FAQ’S</a></li>
        <li><a href="#">Testimonial</a></li>
        <li><a href="#">Terms & Conditions </a></li>
      </ul>
    </div>
    <div class="app-download-icon">
      <a href="#">
        <img src="../assets/images/footer-1.png" alt="apple store" />
      </a>
      <a href="#">
        <img src="../assets/images/footer-2.png" alt="google play store" />
      </a>
    </div>
  </section>
</template>

<script setup></script>

<style scoped>
section {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #04000f;
  padding: 5rem;
}

.social-follow {
  display: flex;
  flex-direction: column;
  align-items: center;

  padding: 0;
}

.social-icons {
  display: flex;
  gap: 1rem;
  padding: 0;
}

.footer-list {
  display: flex;
  flex-direction: row;
}

.app-download-icon {
  display: flex;
  gap: 1rem;
}
</style>
