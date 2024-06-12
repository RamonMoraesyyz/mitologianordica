<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/mnemosine.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Mnemósine
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Mnemosine é uma das titânides da mitologia grega, associada à memória e à lembrança. Aqui está mais detalhadamente sobre ela:

            História e Origens: Mnemosine é filha de Urano (o céu) e Gaia (a terra), fazendo parte da primeira geração divina na mitologia grega. Seu nome deriva da palavra grega "mneme", que significa memória.
            Características e Atributos: Mnemosine é frequentemente retratada como uma figura maternal, ligada à preservação da memória e do conhecimento. 
            Ela personifica a capacidade humana de lembrar, registrar e transmitir informações ao longo do tempo.

            <p class="mb-2 text-xl">
                Filhos e Descendência: Mnemosine é mais conhecida por ser a mãe das nove Musas, divindades inspiradoras das artes, ciências e literatura na mitologia grega. As Musas são:
                Calíope: Musa da poesia épica.
                Clio: Musa da história.
                Erato: Musa da poesia lírica e amorosa.
                Euterpe: Musa da música e da poesia lírica.
                Melpômene: Musa da tragédia.
                Polímnia: Musa da poesia sacra e da eloquência.
                Terpsícore: Musa da dança e da poesia coral.
                Talia: Musa da comédia e da poesia bucólica.
                Urânia: Musa da astronomia e da poesia astral.
                Simbologia e Importância: Mnemosine simboliza a importância da memória e do registro histórico na cultura grega. Ela é reverenciada como a fonte de inspiração para as artes e a ciência, pois é através da memória que o conhecimento é preservado e transmitido de geração em geração.
 
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
