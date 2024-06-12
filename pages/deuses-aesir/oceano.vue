<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/oceano.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Oceano
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Oceano era filho de Urano (o céu) e Gaia (a terra), tornando-o irmão dos Titãs. 
            Ele personificava o oceano que circundava a terra, sendo uma divindade primordial das águas. 
            Na mitologia, ele era frequentemente retratado como uma figura majestosa e poderosa, cuja presença era fundamental para a ordem cósmica.

            

            <p class="mb-2 text-xl">
                Oceano era descrito como uma figura colossal, muitas vezes representado como um homem de barba longa e cabelos flutuantes, com uma aparência imponente que refletia sua conexão com as vastas extensões aquáticas. 
                Sua presença era tranquilizadora e misteriosa ao mesmo tempo, simbolizando a profundidade e os segredos dos mares.
            </p>
            <p class="mb-2 text-xl">
                Oceano teve vários filhos, principalmente por sua união com Tétis, uma das Oceânides (ninfas do oceano). Alguns de seus filhos notáveis incluem:

                Oceânides: Ninfas aquáticas que personificavam diferentes aspectos dos corpos d'água, como as fontes, rios e mares.
                Potamoi: Espíritos dos rios, muitas vezes considerados filhos de Oceano e Tétis.
                Oceaninas: Divindades marinhas menores, associadas a lagos e riachos.

                O símbolo mais comum associado a Oceano é a imagem das águas profundas e vastas do oceano em si. Ele também é frequentemente representado com conchas, corais e criaturas marinhas ao seu redor, simbolizando sua conexão com os reinos aquáticos.

                Além disso, a presença de Oceano muitas vezes representava a fronteira entre o mundo conhecido e o desconhecido, enfatizando a importância das águas como uma fonte de vida, mistério e inspiração na mitologia grega.
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