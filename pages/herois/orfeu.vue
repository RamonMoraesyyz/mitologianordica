<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/orfeu.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Orfeu
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Orfeu era filho de Apolo, o deus do sol e das artes, e da musa Calíope, conhecida pela eloquência e poesia. Ele nasceu na Trácia ou na Ilha de Lesbos, dependendo da versão da história, e desde cedo mostrou um talento excepcional para a música.

            

            <p class="mb-2 text-xl">
                Orfeu era um músico extraordinário, dominando a lira e encantando todos os seres vivos e até mesmo a natureza com sua música.
                Sua história mais famosa é a jornada ao submundo em busca de sua amada Eurídice. Ele conseguiu convencer Hades, o deus dos mortos, a permitir que Eurídice voltasse à vida, desde que ele não olhasse para trás até que ambos estivessem fora do submundo. Infelizmente, no momento crucial, Orfeu olhou para trás e Eurídice desapareceu para sempre.
                Além de sua jornada ao submundo, Orfeu teve outras aventuras, como sua participação na expedição dos Argonautas em busca do Velocino de Ouro.

            </p>
            <p class="mb-2 text-xl">
                Uma curiosidade fascinante sobre Orfeu é que sua habilidade musical era tão poderosa que ele podia acalmar feras selvagens, fazer as árvores dançarem e até mesmo mover pedras. Sua música era tão encantadora que dizem que até mesmo as sombras dos mortos no submundo ficavam calmas quando ele tocava.

                Além disso, a história de Orfeu e Eurídice é uma das mais comoventes da mitologia grega, representando temas de amor, perda e a fragilidade da condição humana diante da morte. Suas canções e sua tragédia pessoal tornaram-no uma figura icônica na cultura e na arte ao longo dos séculos.







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