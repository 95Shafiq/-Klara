<script setup>
import { RouterView } from "vue-router";
import TheNavigation from "./components/TheNavigation.vue";
</script>

<template>
  <div>
    <header>
      <TheNavigation />
    </header>
    <RouterView />
  </div>
</template>

<style></style>
