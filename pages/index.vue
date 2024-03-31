<!-- <script>
export default {
 
}
</script> -->

<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
    <div class="flex flex-col items-center w-full md:w-1/2 px-8 py-11">

      <h1 class="text-7xl text-center">Mitologia Grega</h1>

      <img src="/welcome.png" alt="Índice" class="mb-8">
    </div>

    <div class="flex flex-col justify-center items-center w-full md:w-1/2 px-12 py-12">
      <p class="text-2xl mb-7 mt-18">O conhecimento da mitologia grega é crucial para compreender a sociedade atual, pois
        ela serve como uma base cultural e literária influente, permeando a arte, a literatura e a linguagem
        contemporâneas.
        As referências mitológicas encontradas em expressões comuns e conceitos universais nos ajudam a interpretar melhor
        a nossa cultura e a entender temas como ética, moralidade e heroísmo.
        Além disso, os mitos gregos trazem reflexões sobre as origens da civilização ocidental e fornecem reflexões
        significativas sobre a natureza humana e os desafios enfrentados pela sociedade moderna.
       </p>

      <p class="text-2xl mb-8 font-bold">A segunda geração de deuses, os oceânicos, filhos dos titãs Crono e Réia:</p>
      <div class="flex flex-wrap justify-center">
        <nuxt-link to="/oceanicos/zeus">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Zeus</button>
        </nuxt-link>
        <nuxt-link to="/oceanicos/hestia">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl  font-bold py-2 px-4 rounded mr-4 mb-4">Héstia</button>
        </nuxt-link>
        <nuxt-link to="/oceanicos/demeter">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl  font-bold py-2 px-4 rounded mr-4 mb-4">Démeter</button>
        </nuxt-link>
        <nuxt-link to="/oceanicos/hera">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Hera</button>
        </nuxt-link>
        <nuxt-link to="/oceanicos/hades">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Hades</button>
        </nuxt-link>
        <nuxt-link to="/oceanicos/poseidon">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Poseidon</button>
        </nuxt-link>
      </div>

      <p class="text-2xl mb-8 font-bold">A terceira geração de deuses, os olímpicos são:</p>
      <div class="flex flex-wrap justify-center">
        <nuxt-link to="/olimpicos/atena">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Atena</button>
        </nuxt-link>
        <nuxt-link to="/olimpicos/apolo">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl  font-bold py-2 px-4 rounded mr-4 mb-4">Apolo</button>
        </nuxt-link>
        <nuxt-link to="/olimpicos/artemis">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl  font-bold py-2 px-4 rounded mr-4 mb-4">Ártemis</button>
        </nuxt-link>
        <nuxt-link to="/olimpicos/hermes">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Hermes</button>
        </nuxt-link>
        <nuxt-link to="/olimpicos/ares">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Ares</button>
        </nuxt-link>
        <nuxt-link to="/olimpicos/hefesto">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Hefesto</button>
        </nuxt-link>
        <nuxt-link to="/olimpicos/afrodite">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Afrodite</button>
        </nuxt-link>
        <nuxt-link to="/olimpicos/dionisio">
          <button
            class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded mr-4 mb-4">Dionísio</button>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<style scoped>
.bg-white {
  background-color: #ffffff;
}

.text-left {
  text-align: left;
}
</style>