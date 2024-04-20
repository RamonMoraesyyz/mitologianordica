<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/reia.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Réia
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Reia, também conhecida como Rhea, é uma figura importante na mitologia grega, principalmente como esposa de Cronos e mãe de muitos dos deuses olímpicos. 

            

            <p class="mb-2 text-xl">
                Reia era uma das doze titãs, filha de Gaia (a Terra) e Urano (o Céu). Ela se tornou conhecida por seu papel na Titanomaquia, a guerra entre os Titãs e os deuses olímpicos. Após Cronos ter usurpado o trono de seu pai Urano, ele temia que um de seus filhos o destronasse, então ele os devorava assim que nasciam. 
                Reia, desesperada, escondeu o último filho, Zeus, e o entregou para ser criado por ninfas e criaturas da montanha.
 
            </p>
            <p class="mb-2 text-xl">
                
                Reia era frequentemente retratada como uma figura materna e protetora, simbolizando a fertilidade, a maternidade e a proteção da família. Ela também era associada à terra cultivável e à natureza.
                Ela teve vários filhos com Cronos, incluindo Héstia, Deméter, Hera, Hades, Poseidon e Zeus. Zeus, o mais jovem, foi o único que escapou do destino de ser devorado por Cronos e, eventualmente, liderou a luta contra os Titãs para estabelecer a supremacia dos deuses olímpicos.
                Reia é frequentemente representada segurando um falcão ou uma coroa, símbolos de sua ligação com o céu e o poder real. Ela também é associada à terra fértil e à agricultura, simbolizando a fertilidade e a renovação da vida.


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