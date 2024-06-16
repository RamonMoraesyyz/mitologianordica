<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses-aesir/baldur.jfif" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Baldur
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          Baldur, também conhecido como Balder ou Baldr, é uma figura importante na mitologia nórdica. Ele é frequentemente descrito como o deus da luz, da pureza e da beleza, sendo amado por todos os deuses e seres humanos. Baldur é filho de Odin, o principal deus do panteão nórdico, e de Frigg, a deusa do amor e da fertilidade.
          Baldur é famoso por sua beleza radiante e sua natureza benevolente. No entanto, ele também é conhecido por sua trágica morte, que é um dos eventos mais importantes na mitologia nórdica. Baldur começou a ter sonhos premonitórios de sua própria morte, o que deixou todos os deuses preocupados. Para protegê-lo, Frigg pediu a todas as coisas do mundo que prometessem não ferir Baldur. No entanto, ela negligenciou um pequeno visco, considerando-o inofensivo.


          <p class="mb-2 text-l">
            Loki, o deus trapaceiro, descobriu essa falha e, disfarçado, obteve essa informação de Frigg. Então, ele fez uma flecha de visco e persuadiu Hoder, o irmão cego de Baldur, a atirá-la em Baldur durante um jogo. A flecha perfurou Baldur, matando-o instantaneamente. A morte de Baldur trouxe grande tristeza aos deuses e é vista como um presságio do Ragnarök, o apocalipse nórdico.

          </p>
          <p class="mb-2 text-l">
            Uma curiosidade interessante sobre Baldur é a tentativa de ressuscitá-lo após sua morte. Hel, a deusa do submundo, concordou em libertar Baldur, desde que todas as coisas no mundo, vivas e inanimadas, chorassem por ele. Todos os seres choraram, exceto uma gigante chamada Thokk, que na verdade era Loki disfarçado, impedindo assim a ressurreição de Baldur.

          </p>
        </label>
      </div>

      <div class="mt-4 text-center">
        <nuxt-link to="/">
          <button class="bg-blue-300 hover:bg-blue-400 text-black text-xl font-bold py-2 px-4 rounded">
            Menu
          </button>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<style scoped>
.bg-brown-dark {
  background-color: #211512;
}
</style>
