<template>
  <section class="about mb-5" id="about">
    <div class="container">
      <h3 class="text-center">About Me</h3>
      <div class="about-content">
        <div class="profile-picture">
          <img src="~assets/img/fotoo.jpg" class="profile-img" alt="dp">
        </div>
        <div class="about-description">
          <p>
            Hello! I'm Fredlina Devhania Kholishah, a passionate web developer with a love for creating dynamic and responsive web applications. 
            I have a strong foundation in HTML, CSS, and JavaScript, and I'm always eager to learn new technologies to enhance my skills.
          </p>
          <p>
            Currently, I am pursuing my studies in Information Technology and working on various projects to improve my coding abilities. 
            I believe in continuous learning and am excited about the possibilities in the tech industry.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
.about {
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

.about-content {
  display: flex;
  align-items: center;
  gap: 30px; 
}

.profile-img {
  max-width: 100px; 
  width: 100%; 
  height: auto; 
  border-radius: 50%; 
  object-fit: cover; 
  border: 2px solid #333;
  }

.about-description {
  flex: 1; 
  color: #333;
}
</style>
