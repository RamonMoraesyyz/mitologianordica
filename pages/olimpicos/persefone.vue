<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/persefone.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Perséfone
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Perséfone, também conhecida como Kore, era filha de Zeus, o rei dos deuses, e Deméter, a deusa da agricultura e das colheitas.
            Sua história mais conhecida está ligada ao mito do rapto de Perséfone por Hades, deus do submundo, enquanto ela colhia flores no campo. Hades a levou para o submundo para ser sua esposa e rainha.
            

            <p class="mb-2 text-xl">
                Perséfone é frequentemente retratada como uma deusa de dualidade, representando tanto a beleza e a juventude (como Kore) quanto a escuridão e a sabedoria (como rainha do submundo).
                Ela é descrita como uma deusa gentil e compassiva, preocupada com o bem-estar dos mortais e a fertilidade da terra.

                Perséfone teve um filho com Hades, chamado Zagreu, que em algumas versões é considerado uma divindade misteriosa associada à fertilidade e ao renascimento.
                Zagreu também é conhecido como Dionísio-Zagreu, uma forma primitiva do deus Dionísio, associado ao vinho, à festividade e à renovação.



            </p>
            <p class="mb-2 text-xl">
                Uma das curiosidades sobre Perséfone está relacionada ao mito que explica a alternância das estações do ano. De acordo com a lenda, quando Perséfone está com sua mãe Deméter na superfície da Terra, a primavera e o verão prosperam, trazendo a vida e a abundância. No entanto, quando ela retorna ao submundo para se juntar a Hades, Deméter lamenta sua ausência, resultando no outono e inverno, um período de dormência e escassez na natureza.
                
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