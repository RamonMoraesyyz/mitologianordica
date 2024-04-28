<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/diomedes.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Diomedes
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Diomedes era filho de Tídeo, rei de Argos, e sua mãe era Deipile. Ele era descendente de Tiestes e, portanto, membro da linhagem de Perseu e Héracles. Diomedes é frequentemente retratado como um dos guerreiros mais valentes e habilidosos da Guerra de Troia.

            

            <p class="mb-2 text-xl">
                Diomedes foi um dos principais heróis gregos que lutaram contra Troia. Ele é especialmente conhecido por suas façanhas durante a guerra, incluindo ferir deuses como Ares e Afrodite com sua lança, em combate direto.
                Durante a Noite da Incursão, Diomedes e Odisseu infiltraram-se no campo troiano e causaram estragos, matando muitos inimigos e espalhando o pânico entre as tropas de Troia.
                Diomedes também participou do plano de Odisseu para roubar o Cavalo de Troia, um dos eventos-chave que levaram à queda da cidade.
                Após a guerra, Diomedes retornou a Argos, onde enfrentou alguns desafios, incluindo disputas de sucessão e questões políticas.

            </p>
            <p class="mb-2 text-xl">
                Diomedes teve filhos, sendo Tersites um dos mais conhecidos. Tersites é mencionado em algumas histórias como um personagem cômico e controverso.


                Uma curiosidade interessante sobre Diomedes é que ele era conhecido por sua inteligência e astúcia, além de sua bravura. Sua habilidade em estratégia e sua determinação em batalha o tornaram uma figura respeitada entre os guerreiros gregos.







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