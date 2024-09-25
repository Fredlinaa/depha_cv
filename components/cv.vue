<template>
    <section class="cv" id="cv">
      <div class="container">
        <h3 class="text-center">Curriculum Vitae</h3>
        <div class="cv-content">
          <div class="personal-info">
            <h4>Personal Information</h4>
            <p><strong>Name:</strong> Fredlina Devhania Kholishah</p>
            <p><strong>Email:</strong> devhania88@gmail.com</p>
            <p><strong>Phone:</strong> +62 822-3015-000</p>
            <p><strong>Address:</strong> Golf No 2, Surabaya, Indonesia</p>
          </div>
  
          <div class="education">
            <h4>Education</h4>
            <ul>
              <li><strong>Bachelor of Information Technology</strong> - Brawijaya University(2023)</li>
            </ul>
          </div>
  
          <div class="experience">
            <h4>Work Experience</h4>
            <ul>
              <li><strong>Intern</strong> - PT Telkom (2022-2023)</li>
            </ul>
          </div>
  
          <div class="skills">
            <h4>Skills</h4>
            <div class="skill-buttons">
              <button class="btn-skill">HTML</button>
              <button class="btn-skill">CSS</button>
              <button class="btn-skill">JavaScript</button>
              <button class="btn-skill">Vue.js</button>
              <button class="btn-skill">C++</button>
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
  .cv {
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
  
  .cv-content {
    line-height: 1.6;
  }
  
  h4 {
    color: #8B4513;
    margin-top: 20px;
  }
  
  ul {
    list-style-type: none;
    padding: 0;
  }
  
  ul li {
    padding: 8px 0;
  }
  
  .skills {
    margin-top: 20px;
  }
  
  .skill-buttons {
    display: flex;
    flex-wrap: wrap;
    gap: 10px; 
  }
  
  .btn-skill {
    background-color: #8B4513; 
    color: white;
    border: none;
    border-radius: 5px;
    padding: 10px 15px;
    cursor: pointer;
    transition: background-color 0.3s, transform 0.2s;
  }
  
  .btn-skill:hover {
    background-color: #6f3c1c; 
    transform: scale(1.05); 
  }
  
  .footer {
    margin-top: 30px;
    font-style: italic;
    color: #555;
  }
  </style>
  