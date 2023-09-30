<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
   <header class="navbar">
    <div>
      <nav>
        <RouterLink to="/">Home</RouterLink> -  
        <RouterLink to="/cards">Cards</RouterLink> -  
        <RouterLink to="/zhones">Zhones</RouterLink> -
        <RouterLink to="/sites">Sites</RouterLink> -
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header> 

  <RouterView />
</template>

<style>
  .navbar {
    background-color: #191919;
    padding: 1.2rem;
  }

  body {
    background-color: #2d2b26;
    color: #decfc7;
    margin: 40px;
  }

  a {
    color: #21ecbb;
  }
</style>