<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/gaia.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Gaia
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Gaia é uma das figuras mais importantes e antigas da mitologia grega, sendo personificada como a própria terra. 
            


            Gaia surgiu no início dos tempos, surgindo do Caos primordial junto com outras divindades primordiais. 
            Ela é considerada uma das primeiras entidades a existir, personificando a terra como um todo, incluindo sua fertilidade, vitalidade e força. Gaia é frequentemente retratada como uma figura maternal e poderosa, essencial para a criação e sustentação do mundo.

            

            <p class="mb-2 text-xl">
                Gaia é descrita como uma divindade colossal, muitas vezes representada como uma mulher majestosa com características naturais, como rochas, plantas e rios, fundidos em seu corpo. Ela personifica a terra em toda a sua diversidade, desde as montanhas até os vales férteis, demonstrando sua conexão íntima com a natureza e seus ciclos.
            </p>
            <p class="mb-2 text-xl">
                Gaia teve uma vasta prole de divindades e seres mitológicos, incluindo os Titãs, os Ciclopes, os Hecatônquiros e outros seres primordiais. Alguns de seus filhos notáveis incluem:
        
                O símbolo mais associado a Gaia é a terra em si, representando a fecundidade, a vida e a sustentação de todos os seres vivos. Ela também é frequentemente simbolizada por elementos naturais como árvores, flores, frutos e animais, refletindo sua conexão com o mundo natural.

                Além disso, Gaia é vista como um símbolo de força e poder criativo, sendo a fonte de toda a vida na mitologia grega. Sua presença está intimamente ligada aos ciclos da natureza e à harmonia entre os elementos do mundo.
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