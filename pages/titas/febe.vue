<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/febe.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Febe
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Febe, é uma figura significativa na mitologia grega, especialmente como uma das titãs e uma deusa associada à lua.  
            


            Febe é filha de Urano (o Céu) e Gaia (a Terra), fazendo parte da primeira geração de divindades na mitologia grega. Ela é irmã de titãs como Reia, Tétis, Cronos e outros. Durante a Titanomaquia, a guerra entre os Titãs e os deuses olímpicos, Febe se aliou aos deuses mais jovens e liderados por Zeus.
            É frequentemente descrita como uma deusa associada à lua, à profecia e à luz. Ela também era considerada uma fonte de sabedoria e conhecimento, sendo muitas vezes identificada como a "Brilhante" ou "Luminosa".

            

            <p class="mb-2 text-xl">
                Febe teve diversos filhos, incluindo Leto e Astéria. Leto é especialmente importante na mitologia por ser mãe de Apolo e Ártemis, dois dos deuses mais reverenciados.
            </p>
            <p class="mb-2 text-xl">
                Como uma deusa associada à lua e à luz, Febe é simbolizada pela própria lua em muitas representações.
                 Ela também é associada à sabedoria, à visão do futuro e à inspiração divina, sendo considerada uma fonte de orientação para os mortais e deuses.
            </p>
          </label>
        </div>
  
        <div class="mt-4 text-center">
          <nuxt-link to="/">
            <button
              class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded"
            >
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