<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <ul class="nav justify-content-center">
  <li class="nav-item">
    <RouterLink to="/" class="nav-link text-navy  active  ">Home</RouterLink>
  </li>
  <li class="nav-item">
    <RouterLink to="/about" class="nav-link text-navy ">About</RouterLink>
  </li>
  <li class="nav-item">
    <RouterLink to="/movies" class="nav-link text-navy ">Movies</RouterLink>
  </li>
  <li class="nav-item">
    <RouterLink to="/signUp" class="nav-link text-navy ">Sign Up</RouterLink>
  </li>
  <li class="nav-item">
    <RouterLink to="/signIn" class="nav-link text-navy ">Sign In</RouterLink>
  </li>
</ul>
  </header>
  <RouterView />
</template>

<style lang="scss">
  @import "@/assets/sass/main.scss";
</style>