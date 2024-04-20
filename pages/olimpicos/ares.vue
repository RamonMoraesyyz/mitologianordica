<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/ares.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Ares
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Ares é um dos deuses da mitologia grega associado à guerra, à violência e à coragem.

            É filho de Zeus, e de Hera, a rainha dos deuses. Ele é irmão de Atena, a deusa da sabedoria e da estratégia militar.
            

            <p class="mb-2 text-xl">
                Ares é o deus da guerra e da batalha, sendo frequentemente retratado como um guerreiro feroz e impetuoso. Ele personifica a brutalidade e a violência dos conflitos armados.
                Ares é venerado por sua coragem e força no campo de batalha. Ele inspira os soldados a enfrentarem seus inimigos com determinação e bravura.


                Ares é frequentemente retratado usando um elmo e uma armadura, símbolos de sua natureza guerreira e sua presença nos campos de batalha.
                Ele empunha uma lança e um escudo, instrumentos típicos de combate que refletem sua habilidade em confrontos armados.
            </p>
            <p class="mb-2 text-xl">
                Ares teve vários filhos na mitologia grega, incluindo:
                Fobos e Deimos: Os gêmeos Fobos e Deimos são os personificações do medo e do terror, frequentemente acompanhando Ares em suas batalhas.
                Harmonia: Filha de Ares e de Afrodite, Harmonia personifica a harmonia e a concórdia, embora sua vida esteja marcada por tragédias.


                Apesar de ser o deus da guerra na mitologia grega, Ares não era invencível e enfrentou várias derrotas em batalhas contra humanos e deuses. 
                Por exemplo, ele foi derrotado por Atena na Guerra de Troia, capturado por Héracles e também perdeu na batalha contra os gigantes na Gigantomaquia. Essas histórias destacam que, mesmo sendo poderoso, Ares tinha suas fraquezas e enfrentava desafios significativos em suas lutas.






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