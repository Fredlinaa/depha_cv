<template>
  <section class="portfolio mb-5" id="portfolio">
    <div class="container">
      <h3 class="text-center">My Portfolio</h3>
      <div class="portfolio-items">
        <div class="portfolio-item">
          <img src="@/assets/img/frog you.jpeg" alt="Project 1" class="portfolio-image" />
          <h4>Project 1: Website E-Commerce</h4>
          <p>Aplikasi e-commerce yang memungkinkan pengguna untuk berbelanja online dengan mudah. Memiliki fitur pencarian, keranjang belanja, dan sistem pembayaran yang aman.</p>
          <a href="#" class="btn btn-primary">View Project</a>
        </div>
        <div class="portfolio-item">
          <img src="@/assets/img/heart deep.jpeg" alt="Project 2" class="portfolio-image" />
          <h4>Project 2: Aplikasi Manajemen Tugas</h4>
          <p>Aplikasi yang membantu pengguna untuk mengatur dan mengelola tugas sehari-hari. Menyediakan fitur penjadwalan dan pengingat untuk meningkatkan produktivitas.</p>
          <a href="#" class="btn btn-primary">View Project</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.portfolio {
  background-color: #ffffff; 
  padding: 40px 20px;
  border-radius: 10px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

h3 {
  color: #8B4513; 
  font-size: 32px;
  margin-bottom: 20px;
}

.portfolio-items {
  display: grid; 
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); 
  gap: 20px; 
}

.portfolio-item {
  background-color: #ffffff; 
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  text-align: center; 
}

.portfolio-image {
  width: 100%; 
  height: auto;
  border-radius: 10px; 
}

.portfolio-item h4 {
  color: #6B4226; 
  font-size: 24px;
}

.portfolio-item p {
  color: #333;
  margin: 10px 0;
}

.btn {
  background-color: #8B4513; 
  color: white;
  text-decoration: none;
  padding: 10px 15px;
  border-radius: 5px;
  transition: background-color 0.3s;
}

.btn:hover {
  background-color: #8B4513; 
}
</style>
