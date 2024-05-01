<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/hidralerne.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Hida de Lerne
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >A Hidra era uma serpente aquática gigantesca, com várias cabeças (geralmente nove, mas em algumas versões do mito, ela tem até cem cabeças). Uma das características mais temidas da Hidra era sua capacidade de regenerar duas cabeças no lugar de uma sempre que uma cabeça era cortada.
            A criatura habitava os pântanos de Lerna, onde a água era envenenada por seu hálito tóxico. Ela representava um grande perigo para os habitantes da região e era temida por sua ferocidade.





            

            <p class="mb-2 text-xl">
                O mito mais conhecido envolvendo a Hidra de Lerna é o segundo trabalho de Hércules. Como parte de seus doze trabalhos, Hércules foi enviado para derrotar a Hidra, que era uma criação de Hera, a esposa ciumenta de Zeus e inimiga de Hércules.
                Ao enfrentar a Hidra, Hércules percebeu que matar a criatura seria uma tarefa desafiadora devido à sua capacidade de regeneração. Ele contou com a ajuda de seu sobrinho Iolau, queimando as cabeças cortadas da Hidra com um tocha para impedir sua regeneração. 








            </p>
            <p class="mb-2 text-xl">
                Para complicar ainda mais a batalha, uma das cabeças da Hidra era imortal. Hércules precisou usar uma espada mágica dada a ele por Atena para finalmente derrotar a criatura e cortar a cabeça imortal, enterrando-a sob uma enorme pedra para evitar que ela regenerasse.










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