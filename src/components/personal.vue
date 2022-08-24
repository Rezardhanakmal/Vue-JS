<script setup>
// import WelcomeItem from './WelcomeItem.vue'
// import DocumentationIcon from './icons/IconDocumentation.vue'
// import ToolingIcon from './icons/IconTooling.vue'
// import EcosystemIcon from './icons/IconEcosystem.vue'
// import CommunityIcon from './icons/IconCommunity.vue'
// import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
<div class="personal">
  <img class="logo" src="@/assets/foto.jpg" alt="" width="200" height="200">
  <div class="cv">
    <h1>Reza Ardhana Akmal</h1>
    <h2>Frontend Developer</h2>
      <br>
    <p>Saya adalah siswa SMK Taruna Bhakti. Jurusan saya di SMK adalah Rekayasa Perangkat Lunak. Saya mampu mendesain web(mockup) dan membuat tampilan web sederhana. Saya bisa bekerja dengan jujur ​​dan dapat diandalkan serta mengambil tanggung jawab atas semua tugas yang telah ditugaskan kepada saya. </p>
  </div>
</div>
<hr>
<div class="personal2">
    <div class="umur">
      <h2>Umur</h2>
      <p>: 17 Tahun</p>
    </div>
    <div class="instagram">
      <h2>Instagram</h2>
      <a href="https://www.instagram.com/rz_ardhana/">: rz_ardhana</a>
    </div>
    <div class="alamat">
      <h2>Alamat</h2>
      <a href="https://goo.gl/maps/BebQezgUwAtMeDyPA">: Jl. H. Nadih No.52, Bakti Jaya, Kec. Sukmajaya, Kota Depok, Jawa Barat 16418</a>
    </div>
    <div class="email">
      <h2>Email </h2>
      <a href="mailto:rezaardhanaakmal@gmail.com">: rezaardhanaakmal@gmail.com</a>
    </div>
    <div class="hp">
      <h2>No Telepon </h2>
      <a href="https://wa.me/6289607519333">: 0896-0751-9333</a>
    </div>
  </div>
</template>

<style scoped>
.personal{
    /* display: flex; */
    margin-top: 2rem;
    text-align: center;
    color: #1c3879;
    font-family: 'Poppins', sans-serif;   
  }

  .personal .cv{
    margin-top: 30px;
  }


  .cv h1{
    font-weight: 700;
    font-size: 30px;
  }

  .cv h2{
    font-weight: 200;
    font-size: 30px;
  }

  .cv p{
    font-weight: 400;
    margin-top: -10px;
    font-size: 18px;
  }

  .logo {
    border-radius: 110px;
    margin-top: -20px;
    
  }

  .personal2{
    color: #1c3879;
    font-family: 'Poppins', sans-serif;  
    margin-top: 33px; 
  }


  .alamat{
    display: flex;
    margin-top: 25px;
  }
  .umur{
    display: flex;
    margin-top: 25px;
  }
  .instagram{
    display: flex;
    margin-top: 15px;
  }

  .email{
    display: flex;
    margin-top: 25px;
  }

  .hp{
    display: flex;
    margin-top: 25px;
  }

  .alamat h2{
    font-size: 20px;
  }
  .alamat a{
    font-size: 20px;
    margin-left: 98px;
  }

  .email h2{
    font-size: 20px;
  }
  .email a{
    font-size: 20px;
    margin-left: 118px;
  }

  .hp h2{
    font-size: 20px;
  }
  .hp a{
    font-size: 20px;
    margin-left: 60px;
  }

   .umur h2{
    font-size: 20px;
  }
  .umur p{
    font-size: 20px;
    margin-left: 118px;
  }

   .instagram h2{
    font-size: 20px;
  }
  .instagram a{
    font-size: 20px;
    margin-left: 68px;
  }

</style>

