<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/eros.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Eros
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Eros é frequentemente retratado como filho de Afrodite, a deusa do amor, e Ares, o deus da guerra, embora em algumas versões seja descrito como nascido de Caos, o princípio primordial do universo. 
            Sua origem está ligada à criação e ao poder do amor na mitologia grega.
            

            <p class="mb-2 text-xl">
                Eros é frequentemente representado como um jovem alado armado com um arco e flechas. Suas flechas podem causar paixão e amor em quem são atingidos, influenciando os sentimentos dos deuses e mortais.
                Eros desempenha um papel significativo na mitologia grega, muitas vezes sendo responsável por despertar sentimentos de amor e desejo entre os deuses e entre mortais e deuses. Suas intervenções amorosas muitas vezes têm consequências tanto positivas quanto negativas.
                Eros é central em várias histórias mitológicas, incluindo seu papel na união de Psiquê e Eros, onde ele desafia a vontade de Afrodite para buscar seu próprio amor verdadeiro.
                frequentemente associado a outros deuses do amor, como Anteros (o amor correspondido) e Hímen, o deus do casamento.
            </p>
            <p class="mb-2 text-xl">
                Uma curiosidade interessante sobre Eros é que sua representação e interpretação variaram ao longo do tempo na mitologia grega. 
                Inicialmente, ele era retratado como um deus primordial do caos e da criação, mas ao longo dos séculos, sua figura se tornou mais associada ao amor romântico e à paixão.
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