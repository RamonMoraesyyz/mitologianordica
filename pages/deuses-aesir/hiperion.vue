<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/hiperion.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Hiperion
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Hiperion é frequentemente retratado como um deus majestoso e poderoso, associado à luminosidade do sol e à energia vital que ele proporciona à Terra. Sua figura é vista como radiante e brilhante, refletindo sua natureza como uma divindade solar.
            Hiperion teve vários filhos importantes na mitologia grega, incluindo:

            Hélio (ou Helios): O deus do sol, muitas vezes identificado diretamente com Hiperion devido à sua associação solar.
            Selene: A deusa da lua, irmã de Hélio, que personifica a luz lunar e o ciclo lunar.
            Eos: A deusa da aurora, representando a luz da manhã e o início de um novo dia.

            <p class="mb-2 text-xl">
                Como deus do sol e da luz, Hiperion é simbolicamente associado à iluminação, ao conhecimento, à visão e à energia vital. Sua presença na mitologia reflete a importância do sol como fonte de vida e renovação na compreensão dos antigos gregos sobre o mundo natural.

                Além disso, Hiperion simboliza a ordem cósmica e a regularidade dos fenômenos celestiais, como o nascer e o pôr do sol, contribuindo para a harmonia do universo segundo a visão mitológica grega.
 
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