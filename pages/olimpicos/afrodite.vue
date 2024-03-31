<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/afrodite.png" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Afrodite
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Afrodite é uma das deusas mais importantes da mitologia grega, associada ao amor, à beleza, à fertilidade e à paixão. 

            Existem diferentes versões sobre a origem de Afrodite na mitologia grega. Uma das mais conhecidas é que ela é filha de Urano (o céu) e nasceu da espuma do mar, perto da ilha de Chipre. Outra versão afirma que ela é filha de Zeus e Dione, uma das titânides.
            

            <p class="mb-2 text-xl">
                Afrodite é venerada como a deusa do amor e da beleza. Ela exerce grande influência sobre os relacionamentos amorosos e as paixões humanas, inspirando sentimentos de desejo e afeto.
                Afrodite foi casada com Hefesto, o deus do fogo e da metalurgia. No entanto, ela teve vários amantes divinos e mortais ao longo da mitologia grega, incluindo Ares, o deus da guerra.
                É vista como protetora das mulheres, especialmente durante a gravidez e o parto. Ela também está associada à fertilidade e à reprodução.



            </p>
            <p class="mb-2 text-xl">
                Seus símbolos incluem a concha e a espuma do mar, representando sua origem e conexão com o mar e a fertilidade.
                Afrodite também é associada à pomba, símbolo do amor e da paz, e às rosas, flores que representam a beleza e o romance.


                Afrodite teve vários filhos na mitologia grega, incluindo:
                Eros (ou Cupido): O deus do amor e do desejo, frequentemente retratado como um jovem alado com arco e flechas.
                Harmonia: Deusa da harmonia e da concórdia, filha de Afrodite e Ares.
                Eneias: Um herói troiano e ancestral lendário dos romanos, filho de Afrodite e Anquises.

                
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