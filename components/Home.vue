<template>
    <section class="home mb-5" id="home">
      <div class="background-image">
        <div class="container text-center">
          <div class="card">
            <div class="card-body">
              <h1 class="display-4">Welcome to My Portfolio</h1>
              <p class="lead">I am Fredlina Devhania Kholishah, a passionate Information Technology student.</p>
              <a href="#contact" class="btn contact-btn">Contact Me</a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style scoped>
  .home {
    position: relative;
    padding: 100px 20px;
  }
  
  .background-image {
    background-image: url('@/assets/img/lanaa.jpg'); 
    background-size: cover;
    background-position: center;
    height: 100vh; 
    display: flex;
    justify-content: center;
    align-items: center;
    filter: brightness(0.7); 
  }
  
  .card {
    background: rgba(255, 255, 255, 0.9); 
    border-radius: 20px; 
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2); 
    transition: transform 0.3s, box-shadow 0.3s;
    max-width: 600px; 
    width: 90%; 
    backdrop-filter: blur(10px); 
  }
  
  .card:hover {
    transform: translateY(-10px); 
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.3); 
  }
  
  .card-body {
    padding: 40px; 
    text-align: center; 
  }
  
  h1 {
    color: #2c3e50; 
    text-shadow: 2px 2px 8px rgba(255, 255, 255, 0.8); 
    font-family: 'Playfair Display', serif; 
  }
  
  .lead {
    color: #34495e; 
    margin: 20px 0; 
    font-family: 'Roboto', sans-serif; 
  }
  
  .contact-btn {
    background: linear-gradient(135deg, #555, #63666A); 
    color: white; 
    padding: 15px 40px; 
    border: none; 
    border-radius: 50px; 
    font-size: 20px; 
    font-weight: bold; 
    text-transform: uppercase; 
    letter-spacing: 1px; 
    transition: background 0.3s, transform 0.3s, box-shadow 0.3s;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2); 
  }
  
  .contact-btn:hover {
    background: linear-gradient(135deg, #6B4226, #fff8f0); 
    transform: scale(1.05); 
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3); 
  }
  </style>
  