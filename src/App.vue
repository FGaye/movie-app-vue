<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class=" align-content-center px-5 py-2 bg-white">
      <nav class="navbar align-content-lg-end mx-5 px-lg-5  ">
        <div class="container-fluid px-5 mx-5  align-content-lg-end ">
          <RouterLink to="/" class="nav-link text-navy fw-bolder ">Home</RouterLink>
          <RouterLink to="/about" class="nav-link text-navy fw-bolder">About</RouterLink>
          <RouterLink to="/movies" class="nav-link text-navy fw-bolder">Movies</RouterLink>
          <RouterLink to="/signUp" class="nav-link text-navy fw-bolder">Sign Up</RouterLink>
          <RouterLink to="/signIn" class="nav-link text-navy fw-bolder">Sign In</RouterLink>
        </div>
      </nav>
    </div>
    
  </header>
  <RouterView />
</template>

<style lang="scss">
  @import "@/assets/sass/main.scss";
</style>