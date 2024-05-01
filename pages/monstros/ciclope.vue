<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/ciclope.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Ciclopes
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >De acordo com alguns mitos, os ciclopes eram filhos de Urano (o céu) e Gaia (a terra), nascidos antes dos deuses do Olimpo. Urano, temendo a grandeza e força dos ciclopes, os aprisionou no Tártaro, uma região mais profunda do submundo. Mais tarde, durante a Titanomaquia (a guerra entre os Titãs e os deuses do Olimpo), Zeus libertou os ciclopes do Tártaro como parte de seus aliados contra os Titãs.





            

            <p class="mb-2 text-xl">
                Os ciclopes eram conhecidos por suas habilidades especiais, como a forja de armas poderosas. Um dos ciclopes mais famosos é Brontes, que ajudou Hefesto (ou Vulcano, na mitologia romana) a forjar os raios de Zeus, o tridente de Poseidon e o elmo de invisibilidade de Hades.








            </p>
            <p class="mb-2 text-xl">
                Outra história famosa envolvendo ciclopes é a do encontro de Odisseu (Ulisses) com Polifemo, o filho de Poseidon. Polifemo era um ciclope terrível que devorava os marinheiros que se aventuravam em sua caverna. Odisseu, em sua jornada de retorno para Ítaca após a Guerra de Troia, enfrentou Polifemo e usou sua astúcia para escapar da caverna, mesmo depois de cegar o ciclope.










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