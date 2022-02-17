<script setup>
import { RouterView } from "vue-router";
import TheNavigation from "./components/TheNavigation.vue";
</script>

<template>
  <div class="container">
    <header>
      <TheNavigation />
    </header>
    <RouterView />
  </div>
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}
</style>
