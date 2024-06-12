<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/teia.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Téia
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Téia fez parte da primeira geração divina, os Titãs, que governaram o cosmos antes dos deuses olímpicos. 
            Ela se casou com seu irmão Hiperion, o titã do sol, e juntos tiveram vários filhos notáveis. 

            Téia e Hiperion foram pais de diversos filhos, incluindo:

            Hélio (ou Helios): O deus do sol, muitas vezes representado guiando uma carruagem de sol pelo céu.
            Selene: A deusa da lua, frequentemente retratada viajando pelo céu noturno em sua carruagem lunar.
            Eos: A deusa da aurora, responsável por trazer a luz do novo dia.

            <p class="mb-2 text-xl">
                Como mãe das divindades celestiais, Téia é simbolicamente associada à luz, ao ciclo diário do sol e da lua, e ao renascimento diário da natureza. Ela representa a ordem cósmica e a regulação dos padrões naturais, sendo uma figura venerada e respeitada dentro da mitologia grega.
 
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