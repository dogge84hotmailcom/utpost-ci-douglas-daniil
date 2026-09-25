<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { GuidesTours} from "./components/GuidesTours.vue"
</script>

<template>
  <header>
    <RouterLink to="/guider">Utpost</RouterLink>
  </header>
  <main>
    <RouterView />
  </main>
</template>
