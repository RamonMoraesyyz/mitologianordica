<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/medusa.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Medusa
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Medusa era originalmente uma bela mulher, uma das três Górgonas, filhas de Fórcis e Ceto. As Górgonas eram seres monstruosos com cabelos de serpente e a habilidade de transformar em pedra aqueles que olhassem diretamente para elas. Medusa, em particular, foi transformada em uma Górgona como punição de Atena, deusa da sabedoria e da guerra, por ter tido relações amorosas com Poseidon no templo de Atena.
            A característica mais marcante de Medusa era sua cabeça, com serpentes em vez de cabelos. Seu olhar era mortal, transformando qualquer pessoa em pedra. Essa característica a tornava temida por muitos.




            

            <p class="mb-2 text-xl">
                O mito mais conhecido sobre Medusa envolve Perseu, o herói que foi enviado em uma missão para trazer a cabeça de Medusa como presente para o rei Polidectes. Com a ajuda de deuses como Hermes e Atena, Perseu conseguiu obter uma espada mágica e um escudo polido como um espelho.
                Ele usou o escudo como um espelho para não olhar diretamente para Medusa, evitando assim seu olhar petrificante. Com a ajuda do escudo, Perseu foi capaz de se aproximar de Medusa sem olhar diretamente para ela e cortar sua cabeça. Quando Medusa morreu, Pégaso, o famoso cavalo alado, e Crisaor, um gigante armado, surgiram de seu corpo.




            </p>
            <p class="mb-2 text-xl">
                A cabeça de Medusa, agora capaz de petrificar até mesmo em sua morte, foi usada por Perseu em várias ocasiões, incluindo para salvar Andrômeda do monstro marinho Ceto. Eventualmente, a cabeça de Medusa foi entregue a Atena, que a colocou em seu escudo, o Égide, como um símbolo de poder.
                A história de Medusa é complexa e cheia de simbolismos. Ela representa tanto o perigo mortal quanto a capacidade de superação através da coragem e da astúcia, como demonstrado por Perseu ao derrotá-la.










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