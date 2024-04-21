<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/prometeu.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Prometeu
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Prometeu é uma figura proeminente na mitologia grega, conhecido por seu papel como protetor da humanidade e por trazer o fogo aos mortais. Aqui está mais detalhadamente sobre ele:

            Prometeu é filho do titã Jápeto e da titânide Clímene, fazendo parte da segunda geração de titãs na mitologia grega. Seu nome significa "o que pensa antes" ou "o que vê antes", indicando sua capacidade de prever eventos futuros.

            

            <p class="mb-2 text-xl">
                Prometeu é descrito como um titã inteligente, astuto e criativo. Ele era conhecido por sua habilidade de prever o futuro e sua mente perspicaz, capaz de encontrar soluções para desafios complexos.

                Um de seus feitos mais conhecidos é ter roubado o fogo dos deuses e entregado aos humanos, permitindo que eles desenvolvessem a tecnologia, a civilização e as artes.
                Por desafiar Zeus e ajudar os humanos, Prometeu foi punido severamente. Zeus ordenou que ele fosse acorrentado a uma rocha no Monte Cáucaso, onde uma águia devoraria seu fígado todos os dias, apenas para ele se regenerar à noite, perpetuando seu sofrimento.
            </p>
            <p class="mb-2 text-xl">
                Prometeu é frequentemente associado a Deucalião, o sobrevivente do dilúvio na mitologia grega, e a Pandora, a primeira mulher criada pelos deuses. Ele também é mencionado como pai de Deucalião e de outros filhos em algumas versões mitológicas.
                Simbologia e Importância: Prometeu é um símbolo de inteligência, criatividade e rebelião contra o status quo. Sua história representa a luta pela liberdade, pelo conhecimento e pela busca do progresso humano. Ele é lembrado como um herói cultural que trouxe benefícios e avanços para a humanidade, apesar das consequências de suas ações desafiadoras.
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