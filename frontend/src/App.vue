<script setup>
import Header from './components/layout/Header.vue'
import Footer from './components/layout/Footer.vue'
</script>

<template>
  <div class="layout">
    <Header />

    <main class="main-content">
      <router-view />
    </main>

    <Footer />
  </div>
</template>

<style>
.layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.main-content {
  flex: 1; /* pushes footer to bottom */
  padding: 20px;
}
</style>
