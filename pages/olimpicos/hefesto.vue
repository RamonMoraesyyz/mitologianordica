<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/hefesto.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Hefesto
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Hefesto é o deus do fogo, da metalurgia, da forja, da tecnologia e dos artesãos.
            É filho de Hera, a rainha dos deuses, embora algumas versões da mitologia o descrevam como filho de Hera e Zeus. Ele é frequentemente retratado como coxo devido a um incidente em que foi atirado do Monte Olimpo por sua mãe Hera, por ser considerado feio.
            

            <p class="mb-2 text-xl">
                Hefesto é conhecido por sua habilidade como artesão e ferreiro. 
                Ele forjou armas e armaduras lendárias para os deuses e heróis, incluindo o raio de Zeus, o escudo de Atena e as flechas de Apolo.
                Além de suas habilidades na metalurgia, Hefesto também era habilidoso na criação de autômatos, criaturas mecânicas vivas que podiam realizar tarefas específicas.
                Hefesto foi responsável pela construção do magnífico palácio dos deuses no Monte Olimpo.
                
                Engenhocas e Armadilhas: Hefesto era conhecido por criar engenhocas elaboradas e armadilhas intricadas usando nós e amarrações. Ele era capaz de projetar mecanismos complexos que envolviam a manipulação precisa de cordas e laços, muitas vezes para proteger seus tesouros ou para surpreender intrusos.

                Artefatos e Ferramentas: Como um artesão habilidoso, Hefesto utilizava nós em muitos de seus artefatos e ferramentas. Por exemplo, ele poderia usar nós complicados em redes de pesca, cordas de navios ou em armaduras especialmente elaboradas para deuses e heróis.

               Magia e Simbolismo: Na mitologia grega, os nós também tinham um significado simbólico e mágico. Eles podiam representar a união e a ligação entre as divindades e os mortais, bem como ter poderes protetores ou encantados quando tecidos por deidades como Hefesto.



            </p>
            <p class="mb-2 text-xl">
                Seus principais símbolos são o martelo e a bigorna, ferramentas usadas em seu trabalho como ferreiro.
                O fogo também é associado a Hefesto, representando tanto sua habilidade em trabalhar com metal quanto seu papel como deus do fogo.
                Hefesto teve vários filhos, incluindo:
                Eucleia: Deusa da boa reputação e da fama.
                Eufemo: Herói que navegou em um navio autônomo construído por Hefesto.
                Palici: Deuses gêmeos associados aos géiseres da Sicília.

                


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