<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/harpia.jpeg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Harpias
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            O termo "Harpias" deriva do grego antigo "harpyiai", que significa "as que raptam". Elas são frequentemente retratadas como filhas de Taumante, um deus marinho, e Electra, uma das Plêiades (estrelas do grupo estelar das Plêiades).
            As Harpias são descritas como seres alados, com rostos femininos, garras afiadas e asas que muitas vezes são retratadas como sujas ou malcheirosas. Elas eram consideradas mensageiras do infortúnio, frequentemente associadas a tempestades e ações violentas.




            

            <p class="mb-2 text-xl">
                Uma das histórias mais conhecidas envolvendo as Harpias é a saga de Jasão e os Argonautas. Durante essa jornada, as Harpias atormentaram o rei Fineu, roubando-lhe a comida sempre que ele tentava comer. Posteriormente, na história de Enéias, elas são retratadas como punidoras, lançando maldições sobre os Troianos.
                As Harpias representam a força da natureza e a imprevisibilidade dos elementos, especialmente do vento e das tempestades. Além disso, sua natureza predatória e voraz as associa a conceitos como a fome e a destruição.









            </p>
            <p class="mb-2 text-xl">
                As Harpias foram frequentemente representadas na arte e na literatura ao longo dos séculos, simbolizando tanto a beleza como a ferocidade. Sua presença na mitologia grega contribui para a riqueza e complexidade do panteão de criaturas míticas e divinas dessa cultura.










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
