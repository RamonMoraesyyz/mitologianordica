<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/quimera.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Quimera
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >A Quimera é descrita como uma criatura com corpo de leão, cabeça de leão (ou cabra, em algumas versões) que expele fogo pelas narinas, e uma cauda de serpente. Essa combinação única de características faz dela um dos monstros mais temidos e poderosos da mitologia.




            

            <p class="mb-2 text-xl">
                Sua origem remonta à linhagem de Tifão e Equidna, ambos monstros primordiais e progenitores de várias criaturas lendárias. Equidna era uma criatura metade mulher e metade serpente, enquanto Tifão era um gigante de força descomunal. Juntos, eles deram à luz a Quimera, entre outros monstros como o Cérbero e a Hidra de Lerna.
                A Quimera habitava a região da Lícia, na Ásia Menor, aterrorizando as populações locais com seu fogo destrutivo e sua ferocidade. Ela era considerada invencível, pois sua pele era impenetrável e seu fôlego ardente causava destruição por onde passava.







            </p>
            <p class="mb-2 text-xl">
                O mito mais famoso envolvendo a Quimera é sua batalha com Belerofonte, um herói conhecido por domar cavalos alados, especialmente Pégaso. Montado em Pégaso, Belerofonte enfrentou a Quimera em uma batalha épica. Com astúcia e coragem, Belerofonte conseguiu lançar uma lança equipada com chumbo derretido na garganta da Quimera, bloqueando suas vias respiratórias e causando sua morte.











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