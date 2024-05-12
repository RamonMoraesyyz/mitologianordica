<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/sereia.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Sereia
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >As sereias são frequentemente descritas como tendo o corpo de pássaros ou peixes e o rosto humano, embora suas características exatas possam variar dependendo da fonte.

            Uma das características mais famosas das sereias é sua voz melodiosa e hipnotizante, capaz de atrair marinheiros e navegadores para perto delas, muitas vezes levando-os à perdição.

            As sereias são frequentemente associadas à tentação, perigo e poder sedutor. Elas representam o perigo das águas desconhecidas e os desafios que os viajantes enfrentam ao navegar pelos mares.




            

            <p class="mb-2 text-xl">
                Origens Mitológicas: As sereias têm origens antigas na mitologia grega, sendo inicialmente associadas às musas do mar e à deusa grega das águas, as oceânides. No entanto, ao longo do tempo, elas se tornaram criaturas mais distintas e ganharam suas próprias histórias e lendas.

                Odisséia de Homero: Uma das primeiras referências escritas às sereias é na Odisséia de Homero, onde Ulisses (também conhecido como Odisseu) e sua tripulação enfrentam o desafio de passar pelas sereias sem serem seduzidos por seus cantos.

                Encontros Marítimos: Na mitologia, as sereias são frequentemente associadas a naufrágios e desastres marítimos, representando os perigos ocultos que podem existir nas águas desconhecidas.







            </p>
            <p class="mb-2 text-xl">
                Origem do Nome: O termo "sereia" tem origens no latim "sirena", que por sua vez deriva do grego "seiren", que significa "aquela que canta".

                Variações Culturais: Além da mitologia grega, as sereias também aparecem em várias outras culturas ao redor do mundo, cada uma com suas próprias interpretações e características únicas.

                Representações na Arte: As sereias são frequentemente representadas na arte, literatura e cultura popular, muitas vezes como símbolos de beleza, perigo e mistério associados aos mares.











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