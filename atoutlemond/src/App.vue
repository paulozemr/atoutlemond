<script setup>
import NavbarApi from './components/NavbarApi.vue'
import { RouterView } from 'vue-router';
import FooterApi from './components/FooterApi.vue'
</script>

<template>
  <NavbarApi />
  
  <FooterApi />
<RouterView />
</template>

<style scoped></style>