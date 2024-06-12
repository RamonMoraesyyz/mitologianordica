<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/epimeteu.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Epimeteu
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Epimeteu é um titã da mitologia grega, irmão de Prometeu e filho de Jápeto e Clímene. Seu nome significa "aquele que pensa depois", em contraste com Prometeu, cujo nome significa "aquele que pensa antes". A história de Epimeteu está intimamente ligada à sua interação com os seres humanos.
            Características e Atributos: Epimeteu é frequentemente retratado como um ser impulsivo e despreocupado, em contraste com a astúcia e previsão de seu irmão Prometeu. 
            Ele é conhecido por agir sem pensar nas consequências, o que muitas vezes leva a situações problemáticas.
            

            <p class="mb-2 text-xl">
                Segundo alguns mitos, Epimeteu foi encarregado por Zeus de criar os animais e os seres humanos e dar-lhes habilidades e características. No entanto, Epimeteu distribuiu todas as qualidades positivas entre os animais e deixou os humanos sem defesas, o que levou Prometeu a intervir para ajudar a humanidade.
            </p>
            <p class="mb-2 text-xl">
                Os mitos não mencionam especificamente filhos de Epimeteu. Sua importância está mais relacionada com suas interações com Prometeu, Zeus e os seres humanos.
                Epimeteu é frequentemente visto como um símbolo da impulsividade e da falta de previsão. Sua história destaca a importância da reflexão e do planejamento, contrastando com a sabedoria e a visão estratégica representadas por Prometeu. O mito de Epimeteu também é usado para transmitir lições sobre as consequências de agir sem considerar as repercussões, especialmente em relação às decisões que afetam não apenas a própria vida, mas também a vida de outros.
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