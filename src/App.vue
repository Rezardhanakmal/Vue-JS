<script setup>
  import {
    RouterLink,
    RouterView
  } from 'vue-router'
  import personal from './components/personal.vue'
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <RouterLink to="/">Personal</RouterLink>
        </li>
        <li class="nav-item">
          <RouterLink to="/skill">Skill</RouterLink>
        </li>
      </ul>
    </div>
  </div> 
  </nav>
<br>
  <RouterView />

  <div class="footer">
    <div class="button">
      <a class="btn btn-outline-light" href="https://www.canva.com/design/DAFJqVXxHZM/lNqhX2XvN-7zyCQjg7_QGg/view?utm_content=DAFJqVXxHZM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton#1">Lihat CV</a>
    </div>
  </div>
</template>

<style scoped>

  nav{
    margin-top: 1.5rem;
    height: 50px;
    border-radius: 10px;
  }

  .navbar-nav{
    gap: 1rem;
  }

  .footer{
    background-color: #1c3879;
    width: 1000px;
    height: 100px;
    margin-left: -32px;
    margin-top: 60px;
    border-radius: 0 0 35px 35px;
  }

  .button a{
    width: 100px;
    height: 40px;
    margin: auto;
    margin-bottom: -75px;
  }

  .button{
    text-align: center;
  }
</style>