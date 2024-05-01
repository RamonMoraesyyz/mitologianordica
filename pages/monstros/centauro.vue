<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/centauro.jpg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Centauros
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Os Centauros são criaturas mitológicas da Grécia Antiga, com uma origem e história fascinantes que os tornam únicos no mundo mitológico. São geralmente descritos como seres com metade corpo humano e metade corpo de cavalo, combinando características de ambas as espécies.

            De acordo com a mitologia grega, os Centauros são descendentes de Ixion, um rei mortal, e Néfele, uma nuvem em forma de mulher criada pelos deuses para enganar Ixion. A união de Ixion com Néfele deu origem ao Centauro mais famoso, Quíron.




            

            <p class="mb-2 text-xl">
                Quíron: Ele é o centauro mais conhecido e reverenciado na mitologia grega. Diferente de seus pares, Quíron era sábio, gentil e habilidoso em diversas áreas, como medicina, música, caça e educação. Ele foi o mentor de muitos heróis, incluindo Aquiles, Asclépio e Jasão. Quíron também é conhecido por sua imortalidade temporária e pelo sacrifício que fez para libertar Prometeu.
                Folo: Outro centauro notável é Folo, que também era conhecido por sua sabedoria e habilidades curativas. Ele é lembrado principalmente por sua participação na história de Héracles (Hércules). Durante uma visita de Héracles à sua caverna, Folo serviu vinho, mas uma briga resultou em uma batalha épica com outros centauros e a morte acidental de Folo por uma flecha envenenada.









            </p>
            <p class="mb-2 text-xl">
                A importância desses dois centauros está relacionada à dualidade de sua natureza, mostrando que nem todos os Centauros eram simplesmente seres selvagens. Quíron em particular destaca-se como um símbolo de sabedoria e educação, enquanto Folo é lembrado por sua trágica história com Héracles, exemplificando o lado mais complexo dessas criaturas mitológicas.










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
