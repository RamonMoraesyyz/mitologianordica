<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/locais/delos.jpeg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Ilha de Delos
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Delos era considerada um local sagrado na mitologia grega e foi o centro religioso e comercial dos antigos gregos por séculos. Ela era conhecida como o local de nascimento dos deuses gêmeos Apolo (deus do sol, da música e das artes) e Ártemis (deusa da caça e da natureza selvagem).

            Delos remonta a tempos pré-históricos, mas seu período de maior importância foi entre os séculos VIII e II a.C., quando se tornou um dos principais centros comerciais e culturais do mundo grego. A ilha era conhecida por seu comércio de mercadorias, incluindo escravos, e por suas festividades religiosas em honra a Apolo.




            

            <p class="mb-2 text-xl">
                A ilha é central na mitologia grega por ser o lugar onde Leto, mãe de Apolo e Ártemis, deu à luz. A história conta que Leto, perseguida pela ciumenta Hera, encontrou refúgio em Delos, que antes era uma ilha errante, flutuando pelo mar. Após o nascimento de seus filhos, Delos tornou-se estável e consagrada.











            </p>
            <p class="mb-2 text-xl">
                Nascimento de Apolo e Ártemis: A lenda diz que Leto, após uma longa busca por um local para dar à luz, finalmente encontrou paz em Delos, onde Apolo nasceu primeiro, seguido por Ártemis.

                Os Jogos de Delos: Em honra a Apolo, eram realizados a cada quatro anos, atraindo atletas e visitantes de toda a Grécia.

                Importância Religiosa: Delos era um centro de peregrinação religiosa, onde festivais e rituais em honra a Apolo e Ártemis eram realizados regularmente.

                Declínio: A influência de Delos começou a declinar após o século II a.C., principalmente devido a eventos políticos e mudanças nas rotas comerciais.








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