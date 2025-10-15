<script setup>
const { label, to } = defineProps({
  label: String,
  to: String,
});
</script>

<template>
  <div>
    <a
      :href="to"
      class="flex text-secondary transition-all ease-in-out duration-500 hover:text-accent hover:text-[1.22rem]"
      >{{ label }}</a
    >
  </div>
</template>

<style scoped></style>
