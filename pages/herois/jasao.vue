<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/jasao.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Jasão
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Jasão era filho de Esão, rei de Iolco, na Tessália, e Alcímeda. Seu destino estava ligado ao reino de Iolco e à busca pelo Velocino de Ouro.
            Quando Jasão era jovem, seu tio Pélias usurpou o trono de Iolco e o exilou. Ele foi enviado para ser criado pelo centauro Quíron, onde recebeu uma educação completa e desenvolveu habilidades notáveis.




            

            <p class="mb-2 text-xl">
                O feito mais conhecido de Jasão foi liderar os Argonautas na busca pelo Velocino de Ouro. Ele montou uma expedição com heróis como Hércules, Orfeu e Castor e Pólux, entre outros, em um navio chamado Argo. Durante essa jornada perigosa, eles enfrentaram muitos desafios, incluindo sereias, harpias e o dragão guardião do Velocino.
                Durante a busca pelo Velocino, Jasão conheceu Medeia, uma feiticeira poderosa e filha do rei de Colquida, que os ajudou em sua missão. Jasão acabou se apaixonando por Medeia e, após completar a busca pelo Velocino, casou-se com ela.




            </p>
            <p class="mb-2 text-xl">
                Jasão e Medeia tiveram dois filhos, Mermero e Pólux. No entanto, a história de Jasão e Medeia é marcada por tragédia, incluindo a morte de seus filhos e eventos terríveis resultantes da vingança de Medeia contra Jasão.
                Uma curiosidade interessante sobre Jasão está relacionada ao Velocino de Ouro. O Velocino era o pelo de um carneiro mágico que tinha poderes especiais. A busca pelo Velocino de Ouro simboliza a busca por algo valioso e desafiador, e a história de Jasão e os Argonautas se tornou uma das mais conhecidas e épicas da mitologia grega.










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