<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <header>
    <div class="wrapper">
      <p>
        <RouterLink to="/">Home</RouterLink>
      </p>
      <p>
        <RouterLink to="/about">About</RouterLink>
      </p>
    </div>
  </header>
  <RouterView />
</template>
