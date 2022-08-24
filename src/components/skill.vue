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

<div class="judul">
  <h1>Keahlian</h1>
</div>

<div class="bar">
  <div class="bardua">
      <div class="progress">
        <div class="progress-bar bg-danger" role="progressbar" style="width: 85%" aria-valuenow="85" aria-valuemin="0"
          aria-valuemax="100">
        </div>
      </div>
  <h1>HTML</h1>
  </div>
  
  <div class="bardua">
      <div class="progress">
        <div class="progress-bar bg-success" role="progressbar" style="width: 75%" aria-valuenow="75" aria-valuemin="0"
          aria-valuemax="100">
        </div>
      </div>
  <h1>CSS</h1>
  </div>

  <div class="bardua">
      <div class="progress">
        <div class="progress-bar bg-warning" role="progressbar" style="width: 90%" aria-valuenow="90" aria-valuemin="0"
          aria-valuemax="100">
        </div>
      </div>
  <h1>Figma</h1>
  </div>

  <div class="bardua">
      <div class="progress">
        <div class="progress-bar bg-primary" role="progressbar" style="width: 80%" aria-valuenow="80" aria-valuemin="0"
          aria-valuemax="100">
        </div>
      </div>
  <h1>Bootstrap</h1>
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











  .bar{
    width: 950px;
    height: 220px;
  
    
  }
  .progress{
    height: 30px;
    width: 780px;
    margin-right: 30px;
  }

  .judul h1{
    color: #1c3879;
    text-align: center;
    font-weight: 700;
    font-family: 'Poppins', sans-serif;
    font-size: 30px;
  }

  .bar h1{
    font-size: 25px;
    color: #1c3879;
    font-family: 'Poppins', sans-serif;
  
  }

  .bardua{
    display: flex;
    margin-top: 25px;
  }
</style>