<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2 flex items-center justify-center">
        <img src="/hades.jpg" class="w-full h-screen md:h-auto object-cover" />
      </div>
  
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">Hades</h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            <p>Hades, é o deus do submundo e dos mortos. É frequentemente retratado como um personagem sombrio e temido devido à natureza de seu reino e ao seu papel como juiz das almas dos falecidos. No entanto, há equívocos comuns sobre sua aparência que surgiram ao longo do tempo.

            Em muitas representações contemporâneas, Hades é retratado como uma figura malévola, muitas vezes equiparado ao diabo cristão, com chifres, pele escura e uma aparência grotesca. Essa representação é em grande parte imprecisa e baseada em interpretações errôneas.

            Na verdade, na mitologia grega clássica, Hades não era descrito como uma figura monstruosa, mas sim como um deus imponente e austero, digno de respeito e temor, mas não necessariamente maligno. Ele era frequentemente associado ao mundo subterrâneo, onde reinava com sua esposa Perséfone, mas sua aparência exata não era descrita em detalhes nas antigas fontes mitológicas.

            Além disso, Hades não era um deus da morte, mas sim o deus do submundo, responsável por governar sobre os mortos e presidir os julgamentos das almas. Ele desempenhava um papel importante na mitologia como uma figura que mantinha o equilíbrio entre os reinos dos deuses, dos mortais e dos espíritos.

            Em resumo, os equívocos sobre a aparência de Hades frequentemente surgem de interpretações modernas e da influência de outras tradições religiosas e culturais. Na mitologia grega original, ele era uma figura poderosa e respeitada, cujo domínio sobre o submundo era essencial para a ordem do universo.</p>
          </label>
        </div>
  
        <div class="mt-4 text-center">
          <nuxt-link to="/">
            <button class="bg-zinc-300 hover:bg-zinc-400 text-black font-bold py-2 px-4 rounded">
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