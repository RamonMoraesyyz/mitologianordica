<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/climede.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Clímene
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Clímene é frequentemente identificada como uma titânide, filha de Oceano e Tétis, o que a torna uma das deusas primordiais da mitologia grega.
            Em algumas versões, ela é considerada como a mãe de Prometeu e Epimeteu, tornando-se assim uma figura central na linhagem dos titãs e no mito da criação da humanidade.

            Como uma titânide, Clímene é associada à vastidão e à imensidão dos oceanos, refletindo sua origem como filha de Oceano, a personificação dos mares.
            Ela é frequentemente descrita como uma deusa poderosa e maternal, ligada às forças naturais e à fertilidade.

            <p class="mb-2 text-xl">
                A descendência de Clímene varia dependendo da versão do mito. Em algumas tradições, ela é mãe de Prometeu e Epimeteu, os titãs conhecidos por sua relação com a humanidade e com Zeus.
                Outras fontes sugerem que Clímene teve outros filhos, como Atlas, Menécio e Egeu, embora esses nomes possam ser atribuídos a outras figuras em diferentes mitologias.

                Clímene simboliza a conexão entre os aspectos divinos e terrenos, representando a influência dos titãs nas forças naturais e no mundo humano.
                Sua associação com Prometeu e Epimeteu destaca seu papel na criação e na evolução da humanidade, bem como nas relações entre os deuses olímpicos e os titãs.
 
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