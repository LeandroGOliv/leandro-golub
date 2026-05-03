<script setup>
const { icon, name } = defineProps({
  icon: String,
  name: String,
});

const languages = [{}];
</script>

<template>
  <div class="h-24 w-24 bg-white">
    <img :src="icon" :alt="name" />
  </div>
</template>
