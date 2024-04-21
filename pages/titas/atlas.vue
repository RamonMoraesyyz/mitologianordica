<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/atlas.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Atlas
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Atlas é um titã associado com a luta dos titãs contra os deuses olímpicos. 
            Ele é filho de Jápeto e Clímene, fazendo parte da segunda geração de titãs.
             Após a Titanomaquia, a guerra entre os titãs e os olímpicos, Atlas foi condenado por Zeus a sustentar os céus eternamente.

             Atlas é frequentemente retratado como um titã de grande força e resistência. 
             Sua imagem icônica é a de um gigante segurando o globo celeste em seus ombros, simbolizando o peso e a responsabilidade de suportar o mundo.
            

            <p class="mb-2 text-xl">
                Após a derrota dos titãs, Zeus castigou Atlas obrigando-o a sustentar os céus para toda a eternidade. Essa tarefa árdua é frequentemente representada como um fardo insuportável.
            </p>
            <p class="mb-2 text-xl">
                Atlas é associado com diversas figuras mitológicas. Uma de suas filhas famosas é Calipso, uma ninfa que aparece na "Odisseia" de Homero. Alguns relatos mencionam outras filhas e filhos, como as Hespérides, as ninfas guardiãs das maçãs de ouro no Jardim das Hespérides.
                Atlas é um símbolo de carga pesada, responsabilidade e fardo eterno. Sua imagem como o titã que segura os céus é utilizada frequentemente para representar o peso do mundo ou a responsabilidade imensa que uma pessoa ou entidade pode ter que suportar.
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