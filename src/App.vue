<script setup>
import { /*RouterLink*/ RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";
import FooterBar from "./components/FooterBar.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <NavBar />
    </div>
  </header>
  <ContentBar />
  <FooterBar />
  <RouterView />
</template>
