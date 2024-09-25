<template>
    <section class="profile mb-5" id="profile">
      <div class="container">
        <h3 class="text-center">Profile</h3>
        <div class="profile-content">
          <div class="profile-details">
            <h4>Personal Information</h4>
            <ul>
              <li><strong>Name:</strong> Fredlina Devhania Kholishah</li>
              <li><strong>Date of Birth:</strong> July 8, 2004</li>
              <li><strong>Address:</strong> Golf, Surabaya, Indonesia</li>
              <li><strong>Major:</strong> Information Technology</li>
              <li><strong>Batch:</strong> 2023</li>
            </ul>
          </div>
          <div class="profile-skills">
            <h4>Skills</h4>
            <div class="skills">
              <button class="skill-button">HTML</button>
              <button class="skill-button">CSS</button>
              <button class="skill-button">JavaScript</button>
              <button class="skill-button">Vue.js</button>
              <button class="skill-button">C++</button>
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
  .profile {
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
  
  .profile-content {
    display: flex;
    justify-content: space-between;
    gap: 30px;
  }
  
  .profile-details,
  .profile-skills {
    flex: 1;
  }
  
  .profile-details h4,
  .profile-skills h4 {
    color: #6B4226;
  }
  
  ul {
    list-style-type: none;
    padding: 0;
  }
  
  .skill-button {
    background-color: #6B4226;
    color: white;
    border: none;
    border-radius: 5px;
    padding: 10px 15px;
    margin: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
  }
  
  .skill-button:hover {
    background-color: #8B4513;
  }
  </style>
  