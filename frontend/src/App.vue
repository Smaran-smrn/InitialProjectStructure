<script setup>
import api from "./services/api";
import { onMounted } from "vue";

onMounted(async () => {
  const res = await api.get("/");
  console.log(res.data);
});
</script>

<template>
  <h1>Vue Frontend Running...</h1>
</template>
