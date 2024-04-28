<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/ulisses.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Ulisses
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Ulisses, também conhecido como Odisseu na mitologia grega, é um herói famoso por suas habilidades astutas e pela saga de sua jornada de retorno para casa após a Guerra de Troia. Aqui estão alguns aspectos importantes sobre ele:
             Ulisses foi educado por seu mentor Mentor (daí a origem da palavra "mentor" para designar um guia ou tutor), além de ter aprendido muito com a deusa Atena. Ele era conhecido por sua eloquência e astúcia desde cedo.



            

            <p class="mb-2 text-xl">
            Ulisses desempenhou um papel crucial na Guerra de Troia, destacando-se por sua inteligência estratégica e engenhosidade. Seu plano do Cavalo de Troia, que levou à queda da cidade, é uma das estratégias mais famosas da história.
            A história de Ulisses é principalmente contada na obra "A Odisseia", de Homero. Depois da guerra, ele enfrentou uma longa jornada de volta para Ítaca, enfrentando vários perigos e desafios, como a ilha da feiticeira Circe, o canto das sereias, a passagem entre Escila e Caríbdis e a estadia prolongada na ilha de Calipso.



            </p>
            <p class="mb-2 text-xl">
            Ulisses teve um filho com sua esposa Penélope, chamado Telêmaco. Telêmaco desempenha um papel significativo na "Odisseia", especialmente na busca por seu pai após sua longa ausência.
            Uma curiosidade interessante sobre Ulisses é seu encontro com o ciclope Polifemo durante sua jornada de volta para casa. Ulisses e seus homens ficaram presos na caverna de Polifemo, e Ulisses, usando sua astúcia, embriagou o ciclope e conseguiu cegá-lo para escapar. Este episódio demonstra a inteligência e a habilidade estratégica de Ulisses, características que o tornaram uma figura lendária na mitologia grega.









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