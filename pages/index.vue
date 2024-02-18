<template>
  <div class="bg-brown-dark min-h-screen flex flex-col justify-center items-center text-white">
    <h1 class="text-5xl font-bold mb-9 text-center">Mitologia Grega</h1>

    <p class="text-lg mb-8 text-center">O conhecimento da mitologia grega é crucial para compreender a sociedade atual, pois ela serve como uma base cultural e literária influente, permeando a arte, a literatura e a linguagem contemporâneas. 
      As referências mitológicas encontradas em expressões comuns e conceitos universais nos ajudam a interpretar melhor a nossa cultura e a entender temas como ética, moralidade e heroísmo. 
      Além disso, os mitos gregos oferecem insights sobre as origens da civilização ocidental e fornecem reflexões significativas sobre a natureza humana e os desafios enfrentados pela sociedade moderna.
      O objetivo do projeto é ser um catálogo da mitologia grega com breves descrições dos personagens e para ilustrar, imagens geradas por IA.</p>

    <p class="text-lg mb-8 text-center font-bold">Primeira geração de deuses, os olimpianos, filhos dos titãs Crono e Réia:</p>
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
</template>

<script>
export default {
 
}
</script>

<style scoped>

.bg-brown-dark {
  background-color: #211512; 
}


@import url('https://fonts.googleapis.com/css2?family=GFS+Neohellenic:ital@1&display=swap');


body {
  font-family:  GFS Neohellenic; 
}
</style>