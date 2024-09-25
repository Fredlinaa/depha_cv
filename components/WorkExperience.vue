<template>
    <section class="work-experience mb-5" id="work-experience">
      <div class="container">
        <h3 class="text-center">Work Experience</h3>
        <div class="experience-item">
          <h4>Praktik Kerja Lapangan (PKL)</h4>
          <h5>PT Telkom</h5>
          <p class="date">Desember 2022 - April 2023</p>
          <ul class="responsibilities">
            <li><strong>Penginputan Data ODP:</strong> Bertanggung jawab untuk mengumpulkan dan menginput data terkait ODP (Optical Distribution Point) ke dalam sistem perusahaan, memastikan akurasi dan kelengkapan informasi.</li>
            <li><strong>Jaringan:</strong> Terlibat dalam pemeliharaan dan pengelolaan jaringan fiber optik, serta membantu dalam pengaturan dan pengujian konektivitas jaringan.</li>
            <li><strong>Coding ODP:</strong> Mempelajari dan menerapkan pemrograman dasar untuk pengembangan aplikasi yang mendukung manajemen ODP, termasuk menulis skrip sederhana untuk automasi tugas.</li>
          </ul>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style scoped>
  .work-experience {
    background-color: #ffffff; 
    padding: 40px 20px;
    border-radius: 10px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
  }
  
  h3 {
    color: #8B4513; 
    margin-bottom: 20px;
  }
  
  .experience-item {
    margin-bottom: 30px;
  }
  
  h4 {
    color: #6B4226; 
    font-size: 24px;
  }
  
  h5 {
    color: #8B4513; 
    font-size: 20px;
    font-weight: normal;
  }
  
  .date {
    font-style: italic;
    color: #555;
    margin-bottom: 10px;
  }
  
  .responsibilities {
    list-style-type: none;
    padding: 0;
  }
  
  .responsibilities li {
    margin-bottom: 10px;
    padding-left: 20px;
    position: relative;
  }
  
  .responsibilities li:before {
    content: "✔️"; 
    position: absolute;
    left: 0;
    color: #8B4513; 
  }
  </style>
  