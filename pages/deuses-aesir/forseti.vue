<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses-aesir/forseti.jfif" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Forseti
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-xl">
          Forseti é filho de Balder, o deus da luz e da beleza, e de Nanna, uma deusa associada à paz e à alegria. Ele é frequentemente descrito como um deus justo e imparcial, refletindo as qualidades de seus pais.


          <p class="mb-2 text-xl">
            Forseti é conhecido por vários feitos notáveis:
            Deus da Justiça e da Reconcilição: Forseti é o juiz supremo dos deuses e dos homens. Ele resolve disputas e conflitos, assegurando que a justiça seja feita de maneira imparcial. Ele é conhecido por sua habilidade de encontrar soluções pacíficas e justas, evitando a necessidade de violência.
            Salão de Glitnir: Forseti reside em um salão chamado Glitnir, cujo nome significa "brilhante" ou "resplandecente". Este salão é famoso por seu telhado de prata e pilares de ouro, simbolizando a pureza e a justiça. É neste salão que Forseti ouve casos e resolve disputas, oferecendo um lugar de paz e justiça para todos que o procuram.

          </p>
          <p class="mb-2 text-xl">
            Uma curiosidade interessante sobre Forseti é que ele é considerado um dos deuses mais pacíficos do panteão nórdico. Enquanto muitos deuses nórdicos estão associados à guerra e ao combate, Forseti se destaca por sua natureza pacífica e sua dedicação à justiça e à reconciliação. Isso faz dele uma figura única e respeitada entre os deuses, simbolizando a importância da justiça e da harmonia na sociedade nórdica.

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

  
  <style scoped>
  .bg-brown-dark {
    background-color: #211512;
  }
  </style>