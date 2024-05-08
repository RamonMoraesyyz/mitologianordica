<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/aventuras/odisseia.jpeg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Odisséia
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            A "Odisseia" começa dez anos após o fim da Guerra de Troia. Odisseu (ou Ulisses), rei de Ítaca, parte de Troia com sua frota de navios para retornar para casa.

            Odisseu enfrenta diversas aventuras e desafios em sua jornada de volta a Ítaca.
            Ele e seus companheiros são aprisionados pela feiticeira Circe, que transforma alguns deles em porcos. Com a ajuda do deus Hermes, Odisseu consegue libertar seus homens e permanecer na ilha por um ano.
            Após deixar a ilha de Circe, eles enfrentam as Sereias, monstros marinhos que atraem os marinheiros com suas canções mortais.
            Odisseu também passa pelo estreito das Rochas Planctônicas (Cila e Caríbdis), onde enfrenta escolhas difíceis para salvar sua tripulação.
            Chegando à ilha do deus sol Helios, seus homens desobedecem às ordens de não tocar no gado sagrado, resultando na morte de todos, exceto Odisseu.




            

            <p class="mb-2 text-xl">
                Odisseu é capturado pela ninfa Calipso em sua ilha por sete anos, até ser liberado por ordem dos deuses.
                Ele chega à ilha dos Feácios, onde é bem recebido pela princesa Nausícaa e conta suas aventuras para a corte.
                
                Os Feácios ajudam Odisseu a voltar para Ítaca em um navio. Ele chega disfarçado de mendigo para planejar sua vingança contra os pretendentes que assolam seu reino.









            </p>
            <p class="mb-2 text-xl">
                Com a ajuda de seu filho Telêmaco e de alguns servos leais, Odisseu mata os pretendentes que cobiçam sua esposa Penélope.
                Ele revela sua verdadeira identidade para Penélope, que inicialmente duvida de sua identidade e testa-o.
                Odisseu, finalmente reconhecido por sua esposa, restaura a ordem em Ítaca e se reúne com sua família após muitos anos de ausência.

                A "Odisseia" aborda temas como a astúcia (metis) de Odisseu, a lealdade, o amor familiar, a honra e a justiça.
                Também mostra a influência dos deuses na vida dos mortais, bem como as provações e desafios enfrentados por um herói em sua jornada.









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