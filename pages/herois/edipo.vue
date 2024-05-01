<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/edipo.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Édipo
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Édipo era filho de Laio, rei de Tebas, e Jocasta, rainha de Tebas. O oráculo de Delfos havia previsto que Laio seria morto por seu próprio filho, então ele ordenou que Édipo fosse exposto e abandonado nas montanhas. No entanto, Édipo foi resgatado e criado longe de Tebas, sem saber sua verdadeira origem.

            

            <p class="mb-2 text-xl">
             Quando adulto, Édipo encontrou a cidade de Tebas atormentada pela Esfinge, um monstro que devorava quem não conseguisse resolver seu enigma. Édipo foi capaz de decifrar o enigma da Esfinge e libertar Tebas, o que lhe trouxe fama e reconhecimento na cidade.
             Eventualmente, Édipo descobriu sua verdadeira identidade e o terrível destino que o aguardava: ele era o filho de Laio e Jocasta, e havia cumprido a profecia do oráculo ao matar Laio sem saber quem ele era, casando-se então com Jocasta, sua própria mãe.
             Após a revelação de sua identidade e do trágico conhecimento de seus atos, Édipo se cegou e se exilou, vagando pelo mundo até encontrar o seu fim em uma morte solitária.

            </p>
            <p class="mb-2 text-xl">
                Édipo teve quatro filhos com Jocasta: Etéocles, Polinices, Antígona e Ismênia. Suas histórias também são marcadas por tragédias e eventos dramáticos, especialmente na disputa entre Etéocles e Polinices pelo trono de Tebas.


                Uma curiosidade interessante sobre Édipo é que sua história é uma das tragédias mais conhecidas na mitologia grega e no teatro grego antigo. O mito de Édipo foi amplamente explorado por dramaturgos como Sófocles em sua peça "Édipo Rei", que retrata a jornada trágica do herói em busca da verdade e do destino inevitável.







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