<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/heracles.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Héracles
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Héracles ou Hércules, filho de Zeus e Alcmena, personificava uma fusão única de poderes divinos e humanidade. 
            Sua vida foi marcada por desafios impostos por Hera, que nutria um forte ressentimento devido à sua origem ilegítima, desencadeando uma série de eventos que moldaram sua jornada.
            

            <p class="mb-2 text-xl">
                Na juventude, Hércules demonstrou força e bravura excepcionais. Enfrentou o Leão da Nemeia, a Hidra de Lerna e o javali de Erimanto, entre outros, provando sua valentia e habilidades sobre-humanas.
                 Uma das suas aventuras mais célebres foi a busca pelos Pomos de Ouro, iniciada após um período de insanidade provocado por Hera, levando-o a matar sua esposa e filhos.

                Hércules teve uma ampla descendência, incluindo filhos notáveis como Hebe, deusa da juventude e esposa de Héracles após sua ascensão ao Olimpo, e Hilo, que se tornou rei de Trácia. Seus filhos, cada um com suas habilidades e destinos, contribuíram para a rica tapeçaria da mitologia grega.
            </p>
            <p class="mb-2 text-xl">
                Os 12 trabalhos de Hércules representaram sua penitência e bravura. 
                Derrotar o Leão da Nemeia, matar a Hidra de Lerna, capturar o javali de Erimanto e limpar os estábulos de Áugias foram alguns dos desafios lendários que enfrentou. Ao completá-los, Hércules demonstrou não apenas sua força e coragem, mas também sua capacidade de superar obstáculos aparentemente impossíveis, culminando em sua ascensão ao monte Olimpo, onde foi aceito entre os deuses como um herói imortal.
                Apesar de sua força e bravura, Hércules sempre foi tutelado e ajudado pela deusa Atena.
                Uma curiosidade sobre o significado do seu nome é que o nome "Heracles" em grego antigo é composto por duas partes:

                Hera: O primeiro elemento do nome, "Hera," refere-se à deusa Hera, esposa de Zeus. No entanto, o nome de Heracles não é uma homenagem direta a Hera, mas sim um reflexo da complicada relação entre Heracles e a deusa. Hera foi uma das principais opositoras de Heracles e causou muitos desafios e adversidades em sua vida, o que torna a escolha do nome um tanto irônica.
                Kles: A segunda parte do nome, "kles," significa "glória" em grego. Assim, o nome Heracles pode ser interpretado como "a glória de Hera," embora, ironicamente, ele tenha enfrentado muitos desafios e dificuldades causados diretamente por Hera.





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