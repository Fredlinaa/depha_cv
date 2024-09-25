<template>
  <section class="contact mb-5" id="contact">
    <div class="container">
      <h3 class="text-center">Contact Me</h3>
      <form @submit.prevent="handleSubmit">
        <div class="form-group">
          <label for="name">Name</label>
          <input type="text" class="form-control" id="name" placeholder="Your Name" required>
        </div>
        <div class="form-group">
          <label for="email">Email</label>
          <input type="email" class="form-control" id="email" placeholder="Your Email" required>
        </div>
        <div class="form-group">
          <label for="message">Message</label>
          <textarea class="form-control" id="message" rows="3" placeholder="Your Message" required></textarea>
        </div>
        <button type="submit" class="btn-submit">Send Message</button>
      </form>
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    handleSubmit() {
      alert('Message sent successfully!');
    }
  }
};
</script>

<style scoped>
.contact {
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

.form-group {
  margin-bottom: 15px;
}

label {
  font-weight: bold;
}

input.form-control,
textarea.form-control {
  border-radius: 5px;
  border: 1px solid #ccc;
  padding: 10px;
}

input.form-control:focus,
textarea.form-control:focus {
  border-color: #8B4513; 
  box-shadow: 0 0 5px rgba(139, 69, 19, 0.5); 
}

.btn-submit {
  background-color: #8B4513; 
  color: white;
  border: none;
  border-radius: 5px;
  padding: 10px 15px;
  cursor: pointer;
  transition: background-color 0.3s, transform 0.2s;
}

.btn-submit:hover {
  background-color: #6f3c1c; 
  transform: scale(1.05); 
}
</style>
