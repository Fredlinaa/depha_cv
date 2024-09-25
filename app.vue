<template>
  <div id="app">
    <div class="container">
      <header class="header">
        <div class="logo">
          <img src="@/assets/img/dpe icon.png" alt="Logo" class="logo-img" />
        </div>
        <nav class="nav-menu">
          <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" @click="scroll('home')">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" @click="scroll('profile')">Profile</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" @click="scroll('about')">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" @click="scroll('work-experience')">Work Experience</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" @click="scroll('portfolio')">Portfolio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" @click="scroll('cv')">CV</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" @click="scroll('contact')">Contact</a>
            </li>
          </ul>
        </nav>
      </header>

      <main class="main-content">
        <Home />
        <Profile />
        <About />
        <WorkExperience />
        <Portfolio />
        <CV />
        <Contact />
      </main>
    </div>

    <footer>
      <p>&copy; 2024 Fredlina Devhania Kholishah T3G. All rights reserved.</p>
    </footer>
  </div>
</template>

<script>
import Home from './components/Home.vue';
import Profile from './components/Profile.vue';
import About from './components/About.vue';
import WorkExperience from './components/WorkExperience.vue';
import Portfolio from './components/Portfolio.vue';
import CV from './components/CV.vue';
import Contact from './components/Contact.vue';

export default {
  components: {
    Home,
    Profile,
    About,
    WorkExperience,
    Portfolio,
    CV,
    Contact,
  },
  methods: {
    scroll(section) {
      const element = document.getElementById(section);
      if (element) {
        element.scrollIntoView({ behavior: 'smooth' });
      }
    }
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif; 
  background-color: #f4f4f4; 
  color: #333; 
  min-height: 100vh; 
  display: flex;
  flex-direction: column; 
}

.header {
  position: fixed; 
  top: 0; 
  left: 0; 
  width: 100%; 
  background: linear-gradient(to right, #333, #555); 
  color: white; 
  display: flex; 
  align-items: center; 
  padding: 10px 20px; 
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5); 
  z-index: 1000; 
}

.logo {
  display: flex; 
  align-items: center; 
}

.logo-img {
  max-width: 40px; 
  margin-right: 50px; 
}

.brand-name {
  font-size: 24px; 
}

.nav-menu {
  margin-left: auto; 
}

.nav {
  list-style-type: none;
  padding: 0;
  display: flex; 
}

.nav-item {
  margin: 0 15px; 
}

.nav-link {
  color: white;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s, transform 0.3s;
}

.nav-link:hover {
  color: gold;
  transform: scale(1.1); 
}

.main-content {
  padding: 80px 20px; 
  flex: 1; 
  margin-bottom: 60px; 
}

section {
  background: white; 
  padding: 20px; 
  border-radius: 10px; 
  margin-bottom: 20px; 
}

.btn {
  background-color: #28a745; 
  color: white;
}

.btn:hover {
  transform: scale(1.05); 
}

footer {
  text-align: center; 
  padding: 20px; 
  background-color: #333; 
  color: white; 
  position: relative; 
  width: 100%; 
}

@media (max-width: 768px) {
  .header {
    flex-direction: column; 
    align-items: flex-start; 
  }

  .nav-menu {
    margin-left: 0; 
  }
}
</style>
