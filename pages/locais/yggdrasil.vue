<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/locais/yggdrasil.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Yggdrasil
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Yggdrasil, na mitologia nórdica, é a árvore cósmica que conecta os Nove Mundos. É uma imagem central que simboliza a ordem cósmica e a ligação entre os diferentes reinos da existência. A árvore é descrita como um carvalho gigantesco e perene, cujos galhos se estendem sobre todo o cosmos, suas raízes mergulhando profundamente em três fontes importantes:

            Urdarbrunnr: A fonte da sabedoria, guardada pelas Nornas, as deusas do destino que tecem o destino dos seres vivos.
            Hvergelmir: A fonte de todos os rios, localizada em Niflheim, o reino do gelo.
            Mímisbrunnr: A fonte de Mímir, localizada em Jotunheim, que concede sabedoria e conhecimento aos que bebem dela.

  
  
            <p class="mb-2 text-l">
                Yggdrasil também é o local onde vários seres míticos residem, como a águia que vive em seus galhos superiores e o dragão Nidhogg, que roe suas raízes. Esses seres representam forças naturais e cósmicas que mantêm o equilíbrio do mundo.



  
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade fascinante sobre Yggdrasil é que sua imagem como uma árvore cósmica tem paralelos em muitas outras culturas ao redor do mundo. Árvores sagradas ou cósmicas são encontradas em mitologias de várias tradições, como a Ashvattha na mitologia hindu e a Yaxché na mitologia maia. Essas árvores compartilham a ideia de conexão entre os mundos, representando uma compreensão universal da ligação entre a Terra, o céu e o submundo. Isso ilustra como temas universais de conexão cósmica e ordem estão presentes em diferentes culturas ao longo da história humana.



  
            </p>
          </label>
        </div>
  
        <div class="mt-4 text-center">
          <nuxt-link to="/">
            <button class="bg-blue-300 hover:bg-blue-400 text-black text-xl font-bold py-2 px-4 rounded">
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
  
    
    <style scoped>
    .bg-brown-dark {
      background-color: #211512;
    }
    </style>