<script setup>
import gsap from "gsap";
import ScrollToPlugin from "gsap/ScrollToPlugin";
const props = defineProps({
  label: String,
  to: String,
});

gsap.registerPlugin(ScrollToPlugin);
const handleClick = () => {
  gsap.to(window, { duration: 0.6, scrollTo: props.to });
};
</script>

<template>
  <div>
    <a
      :href="to"
      @click.prevent="handleClick"
      class="flex text-secondary transition-all ease-in-out duration-500 hover:text-accent hover:text-[1.22rem]"
      >{{ label }}</a
    >
  </div>
</template>

<style scoped></style>
