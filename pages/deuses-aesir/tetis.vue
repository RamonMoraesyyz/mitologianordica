<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/tetis.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Tétis
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Tétis é uma das doze titânides, filha de Urano (o céu) e Gaia (a terra). 
            Ela desempenhou papéis importantes em diferentes mitos gregos, sendo frequentemente associada ao mar e à água.
            Tétis é retratada como uma deusa majestosa, muitas vezes descrita como a personificação do mar. Ela é representada como uma figura maternal e protetora, que nutre e cuida dos seres vivos em seu domínio aquático.

            <p class="mb-2 text-xl">
                Tétis é mais conhecida por ser a mãe de algumas figuras importantes da mitologia grega. Seus filhos incluem:
                Aquiles: O herói grego mais famoso da Guerra de Troia, conhecido por sua força, coragem e habilidade como guerreiro.
                Telégono: Filho de Tétis e Ulisses, que mais tarde se encontrou com seu pai sem saber de sua identidade, resultando em um confronto trágico.
                Tétis é frequentemente associada à natureza purificadora e rejuvenescedora da água. Ela também simboliza a conexão entre os domínios terrestre e aquático, sendo uma figura essencial na cosmologia grega antiga.
 
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