<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/locais/valhalla.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Valhalla
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Valhalla, na mitologia nórdica, é o grandioso salão dos guerreiros caídos em combate, localizado em Asgard, o reino dos deuses Æsir. Este lugar é descrito como um salão vasto e majestoso, com quinhentas portas através das quais os guerreiros entram diariamente. Valhalla é governado por Odin, o pai dos deuses, e é onde os guerreiros escolhidos são recebidos após sua morte em batalha.

  
  
            <p class="mb-2 text-l">
                Os guerreiros que entram em Valhalla são conhecidos como Einherjar e são honrados por sua coragem e habilidade no campo de batalha. Lá, eles desfrutam de um banquete interminável, lutam em duelos gloriosos durante o dia e são restaurados para lutar novamente à noite. Valhalla é um lugar de alegria e camaradagem para aqueles que morreram de maneira heroica, onde a batalha é vista como uma celebração de bravura e sacrifício.



  
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade fascinante sobre Valhalla é que, de acordo com algumas interpretações da mitologia nórdica, o número de Einherjar em Valhalla não é fixo. Quando não estão em batalha ou banquete, os guerreiros passam seu tempo treinando e se preparando para o Ragnarök, o fim dos tempos. Durante o Ragnarök, eles serão convocados por Odin para lutar ao seu lado contra as forças do caos e do mal. Assim, Valhalla não é apenas um local de descanso e celebração, mas também um campo de treinamento e preparação para o futuro destino épico dos guerreiros nórdicos.



  
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