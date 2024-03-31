<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/dionisio.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Dionísio
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Dionísio é uma figura fascinante na mitologia grega, associada ao vinho, à fertilidade, ao teatro e aos prazeres extáticos. Aqui estão alguns detalhes sobre ele:

            É frequentemente descrito como filho de Zeus, o rei dos deuses, e de Sêmele, uma mortal. Sua origem é marcada por eventos misteriosos, incluindo a gestação de Sêmele e o 
            nascimento prematuro de Dionísio após ela ter sido consumida pelo fogo divino de Zeus, e o fato dele ter sido gestado na coxa de Zeus, após a morte de sua mãe.
            

            <p class="mb-2 text-xl">
                Dionísio é reverenciado como o deus do vinho, das festas, da fertilidade e das celebrações extáticas. Ele é frequentemente retratado como o promotor do êxtase e da alegria nas festividades.
                Também é associado ao teatro e às artes, sendo considerado o patrono dos dramaturgos, atores e músicos. Os festivais em sua honra, as Dionísias, eram marcados por competições teatrais e apresentações de peças clássicas.
                Dionísio simboliza a ideia de transformação e renascimento, já que o vinho, que ele representa, passa por um processo de fermentação e renovação.



            </p>
            <p class="mb-2 text-xl">
                Seus símbolos incluem o cacho de uvas, que representa o vinho e a fertilidade, e o cálice de vinho, símbolo das festividades e da celebração.
                Dionísio também é associado a títeres e máscaras teatrais, destacando seu papel como patrono das artes cênicas.


               Dionísio teve vários filhos, incluindo:
               Priapo: Um deus da fertilidade e da sexualidade masculina.
               Teatro e Comédia: Alguns autores e historiadores atribuem a Dionísio a paternidade simbólica do teatro e das artes dramáticas.

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