<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <div class="wrapper">
    <nav class="nav__wrapper">
      <div class="logo">Logo</div>
      <div class="links">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="#">Blog</RouterLink>
        <RouterLink to="#">Shop</RouterLink>
        <RouterLink to="#">Pages</RouterLink>
        <RouterLink to="#">Reserve</RouterLink>
        <RouterLink to="#">Contact us</RouterLink>
      </div>
      <div class="icons">Icons</div>
    </nav>
  </div>
</template>

<style lang="scss" scoped>
.nav__wrapper {
  @apply flex gap-28 items-center justify-center py-10 px-4 mx-auto bg-white border-b-2 border-b-amber-700 text-xl  font-medium;

  .links {
    @apply flex gap-8;
  }
}
</style>
