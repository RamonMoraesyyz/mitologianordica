<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/grifo.jpeg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Grifos
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >O Grifo é uma criatura mitológica fascinante da mitologia grega, com origens que remontam à Mesopotâmia e que também aparece em outras culturas ao longo da história. Na mitologia grega, o Grifo é representado como um animal majestoso e poderoso, com um corpo de leão e a cabeça e as asas de uma águia.




            

            <p class="mb-2 text-xl">
                A história e origem do Grifo variam de acordo com as diferentes tradições mitológicas em que é mencionado. No contexto grego, o Grifo muitas vezes é associado à proteção de tesouros e riquezas. Diz-se que ele guarda o ouro das montanhas e protege locais sagrados.
            Os relatos mitológicos sobre o Grifo frequentemente o descrevem como uma criatura poderosa e imponente, capaz de voar e atacar com suas garras afiadas e seu bico forte. Sua figura é frequentemente associada a símbolos de poder, nobreza e proteção.









            </p>
            <p class="mb-2 text-xl">
                Uma das lendas envolvendo o Grifo é sua associação com o reino de Escítia, uma região no norte do Mar Negro. Segundo alguns relatos, os Escitas acreditavam que o Grifo era um guardião de ouro e que eles mantinham uma relação de respeito com essa criatura mítica.
                Ao longo da história, o Grifo apareceu em diversas obras literárias, arte visual e simbolismo cultural. Sua figura é frequentemente usada para representar a união de características fortes e nobres, como a coragem do leão e a visão aguçada da águia.










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
