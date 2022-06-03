<script setup>
import HeaderComp from "@/components/template/HeaderComp.vue";
import FooterComp from "./components/template/FooterComp.vue";
</script>

<template>
  <HeaderComp />
  <RouterView />
  <FooterComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  height: 100vh;
  font-weight: normal;
}

a {
  color: inherit;
  text-decoration: none;
}

main {
  height: 70%;
}
</style>
