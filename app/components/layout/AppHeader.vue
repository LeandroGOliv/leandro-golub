<script setup></script>

<template>
  <header class="flex items-center text-lg bg-primary w-full h-16 px-60">
    <span class="text-secondary uppercase text-2xl whitespace-nowrap"
      >Leandro Golub</span
    >
    <nav class="flex w-full h-full justify-end">
      <ul class="flex items-center gap-10">
        <li>
          <UiNavLink label="Início" to="home" />
        </li>
        <li>
          <UiNavLink label="Sobre" to="about" />
        </li>
        <li>
          <UiNavLink label="Projetos e tecnologias" to="projects-stack" />
        </li>
        <li>
          <UiNavLink label="Contato" to="contact" />
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped></style>
