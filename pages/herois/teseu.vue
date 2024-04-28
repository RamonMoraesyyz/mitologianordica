<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/teseu.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Teseu
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Teseu é filho de Egeu, rei de Atenas, e Etra, princesa de Trezena. Sua concepção é marcada por um episódio famoso envolvendo um par de sandálias e uma espada, que Egeu escondeu sob uma rocha e instruiu Etra a deixar Teseu pegar esses itens quando ele estivesse pronto para reclamar sua herança e legitimar sua linhagem.
             Durante sua juventude, Teseu demonstrou força, coragem e habilidades excepcionais. 
             Ele se tornou conhecido por seus feitos ao longo de sua jornada, incluindo a derrota do infame Touro de Maratona e a libertação de Atenas do tributo cruel de Creta, no qual jovens atenienses eram sacrificados ao Minotauro.

            

            <p class="mb-2 text-xl">
              Um dos feitos mais célebres de Teseu foi entrar no Labirinto de Creta e derrotar o Minotauro, uma criatura meio homem e meio touro que habitava o labirinto. Ele conseguiu essa façanha com a ajuda de Ariadne, filha do rei Minos de Creta, que lhe deu um novelo de linha para ajudá-lo a encontrar o caminho de volta após matar o Minotauro.
              Teseu também participou da famosa expedição das Amazonas ao lado de Hércules. Durante essa aventura, ele encontrou e se casou com a rainha amazona Hipólita, com quem teve um filho chamado Hipólito.

            </p>
            <p class="mb-2 text-xl">
                Além de Hipólito, Teseu teve outros filhos, como Demofonte, Acamas e Estafílo. Demofonte e Acamas são frequentemente mencionados como seus filhos com Fedra, sua segunda esposa. Estafílo é associado a Teseu através de lendas sobre o vinho, já que Estafílo é considerado o inventor da arte de fermentar uvas para fazer vinho.

                Uma curiosidade interessante sobre Teseu é sua conexão com a cidade de Atenas e a origem do costume de içar velas negras em navios retornando de uma expedição perigosa. De acordo com a lenda, Teseu prometeu a seu pai, Egeu, que trocaria as velas brancas por velas negras caso sobrevivesse ao enfrentamento com o Minotauro no Labirinto de Creta. Ao retornar vitorioso, Teseu esqueceu-se de mudar as velas, o que levou Egeu a pensar que seu filho havia morrido. Esse episódio teria originado a tradição de içar velas negras em navios que retornavam de missões arriscadas, como uma forma de comunicar à terra natal se a viagem havia sido bem-sucedida ou não.







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