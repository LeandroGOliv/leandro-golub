<script setup></script>

<template>
  <section
    id="about"
    class="bg-secondary relative flex justify-center items-center"
  >
    <UiWaveTop class="absolute top-0" />
    <h2 class="text-3xl font-semibold w-40 ml-16 mb-100">Sobre</h2>
    <div class="flex h-full">
      <div class="flex-1 flex justify-center items-center pb-10">
        <div
          class="bg-[url(/images/foto-eu.jpg)] w-96 h-96 bg-cover bg-center rounded-tr-4xl rounded-bl-4xl shadow"
        ></div>
      </div>
      <div class="flex-1 flex flex-col justify-center items-center mr-16">
        <p class="text-lg text-textcolor indent-6">
          Sou desenvolvedor front-end com 2 anos de experiência em interfaces
          responsivas, acessíveis e otimizadas. Busco sempre novas tecnologias e
          boas práticas, combinando criatividade, performance e atenção ao
          usuário para entregar experiências digitais de qualidade. Valorizo
          código limpo e soluções eficientes, contribuindo tanto no
          desenvolvimento técnico quanto no fortalecimento da cultura e
          colaboração da equipe, pois acredito que o sucesso de um projeto
          depende tanto da excelência técnica quanto da colaboração genuína
          entre as pessoas.
        </p>
        <div class="flex pt-8 gap-18">
          <div>
            <span class="text-4xl font-bold">2+</span>
            <p>Anos de experiência</p>
          </div>
          <div>
            <span class="text-4xl font-bold">10+</span>
            <p>Projetos concluídos</p>
          </div>
          <div>
            <span class="text-4xl font-bold">10+</span>
            <p>Tecnologias</p>
          </div>
        </div>
      </div>
    </div>

    <UiWaveBottom class="absolute bottom-0" />
  </section>
</template>

<style scoped></style>
