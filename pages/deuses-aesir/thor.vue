<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses-aesir/thor.jpg" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Thor
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-xl">
          Thor é um dos deuses mais importantes da mitologia nórdica, conhecido como o deus do trovão, da força e da proteção. 
          Ele é filho de Odin, o principal deus dos Æsir, e de Jörð, a personificação da Terra. 
          Com sua esposa Sif, Thor tem vários filhos, incluindo Þrúðr (Thrud), conhecida por sua força e beleza. Além disso, Thor tem dois filhos com a giganta Járnsaxa: Magni, famoso por sua imensa força, e Modi, cujo nome significa "coragem".

          <p class="mb-2 text-xl">
            Entre seus feitos mais notáveis, Thor é famoso por empunhar o martelo Mjölnir, uma poderosa arma mágica que ele usa para combater gigantes e proteger Asgard, a fortaleza dos deuses. Em diversas lendas, Thor embarca em aventuras em Jotunheim, a terra dos gigantes, onde enfrenta inimigos e realiza grandes proezas de força e bravura.
          </p>
          <p class="mb-2 text-xl">
            Uma de suas façanhas mais famosas é a batalha contra a serpente gigante Jörmungandr, com quem Thor tem uma inimizade mortal. Durante o Ragnarök, o fim do mundo na mitologia nórdica, Thor finalmente mata Jörmungandr, mas também sucumbe aos ferimentos causados pelo veneno da serpente.

            Uma curiosidade interessante sobre Thor é sua participação na recuperação do hidromel da poesia, um líquido mágico que confere sabedoria e habilidade poética a quem o bebe. Em uma das sagas, Thor ajuda os deuses a recuperar este hidromel, demonstrando não apenas sua força física, mas também sua importância na preservação da sabedoria e cultura dos deuses nórdicos.
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
