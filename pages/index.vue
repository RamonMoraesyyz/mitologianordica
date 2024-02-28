<template>
  <div class="bg-white min-h-screen flex flex-row justify-center items-start text-black">
    <div class="flex flex-col items-center w-1/2 px-8 py-11">

      <h1 class="text-6xl font-bold text-center">Mitologia Grega</h1>

      <img src="/index.png" alt="Índice" class="mb-8">
    </div>

    <div class="flex flex-col justify-center items-center w-1/2 px-12 py-12">
      <p class="text-lg mb-5 mt-15">O conhecimento da mitologia grega é crucial para compreender a sociedade atual, pois ela serve como uma base cultural e literária influente, permeando a arte, a literatura e a linguagem contemporâneas. 
        As referências mitológicas encontradas em expressões comuns e conceitos universais nos ajudam a interpretar melhor a nossa cultura e a entender temas como ética, moralidade e heroísmo. 
        Além disso, os mitos gregos oferecem insights sobre as origens da civilização ocidental e fornecem reflexões significativas sobre a natureza humana e os desafios enfrentados pela sociedade moderna.
        O objetivo do projeto é ser um catálogo da mitologia grega com breves descrições dos personagens e para ilustrar, imagens geradas por IA.</p>

      <p class="text-lg mb-8 font-bold">Primeira geração de deuses, os olimpianos, filhos dos titãs Crono e Réia:</p>
      <div class="flex flex-wrap justify-center">
        <nuxt-link to="/zeus">
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-2 px-4 rounded mr-4 mb-4">Zeus</button>
        </nuxt-link>
        <nuxt-link to="/hestia">
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-2 px-4 rounded mr-4 mb-4">Héstia</button>
        </nuxt-link>
        <nuxt-link to="/demeter">
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-2 px-4 rounded mr-4 mb-4">Démeter</button>
        </nuxt-link>
        <nuxt-link to="/hera">
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-2 px-4 rounded mr-4 mb-4">Hera</button>
        </nuxt-link>
        <nuxt-link to="/hades">
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-2 px-4 rounded mr-4 mb-4">Hades</button>
        </nuxt-link>
        <nuxt-link to="/poseidon">
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-2 px-4 rounded mr-4 mb-4">Poseidon</button>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
 
}
</script>

<style scoped>

.bg-white {
  background-color: #ffffff; 
}

.text-left {
  text-align: left;
}

</style>