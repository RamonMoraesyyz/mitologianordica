<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/japeto.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Jápeto
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Jápeto era um dos titãs da segunda geração na mitologia grega, descendente dos primordiais Urano e Gaia. Ele desempenhou um papel significativo na Titanomaquia, a guerra entre os titãs e os deuses olímpicos liderados por Zeus.
            Como titã, Jápeto era associado a elementos como a força, a estabilidade e o domínio sobre certos aspectos do cosmos. Sua personalidade e características específicas não são tão detalhadas quanto as de alguns de seus irmãos, mas ele é frequentemente retratado como um titã poderoso e respeitado.

            <p class="mb-2 text-xl">
                Jápeto é mais conhecido por ser o pai de alguns dos titãs mais famosos, como Prometeu (o criador da humanidade e defensor dos mortais), Epimeteu (associado às consequências não planejadas) e Atlas (o titã que sustentava os céus).
Simbologia e Importância: Jápeto tem uma simbologia ligada à geração dos titãs e à transição de poder entre as eras mitológicas. Seus filhos desempenham papéis fundamentais na mitologia grega, especialmente Prometeu, cujas ações têm implicações profundas na relação entre deuses e humanos.
 
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