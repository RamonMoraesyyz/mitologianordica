<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/pegaso.jpg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Pégaso
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Pégaso nasceu do sangue derramado quando o herói Perseu decapitou a Medusa, uma das Górgonas, cujo olhar transformava as pessoas em pedra. O cavalo alado emergiu do sangue que caiu sobre o mar e as terras de Líbia, dando origem ao seu nome, que significa "fonte" ou "nascente".
            Pégaso é geralmente retratado como um cavalo branco alado, ágil e majestoso. Suas asas simbolizam a liberdade e a capacidade de transcender os limites terrenos, voando pelos céus e alcançando alturas impossíveis para outros seres.




            

            <p class="mb-2 text-xl">
                Além de sua associação com Perseu, Pégaso também desempenhou um papel significativo na história de Belerofonte. Este herói conseguiu domar Pégaso usando uma rédea de ouro dada pela deusa Atena. Juntos, eles enfrentaram a Quimera, uma criatura monstruosa de corpo leão, cabeça de cabra e cauda de serpente.
                Pégaso é frequentemente interpretado como um símbolo de inspiração e criatividade, especialmente nas artes e na poesia. Sua capacidade de voar representa a busca por conhecimento e a vontade de superar obstáculos. Além disso, sua ligação com fontes de água e nascentes também o associa à vida e à renovação.









            </p>
            <p class="mb-2 text-xl">
                A imagem de Pégaso aparece em diversas formas de arte, desde pinturas e esculturas antigas até obras modernas. Ele é um dos seres mais reconhecíveis e icônicos da mitologia grega, continuando a inspirar histórias e interpretações até os dias de hoje.










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
