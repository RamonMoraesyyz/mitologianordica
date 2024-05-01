<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/cerbero.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Cérbero
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Cerberus era filho de Tifão e Equidna, duas criaturas monstruosas que personificavam forças caóticas e perigosas. Ele era descrito como um enorme cão com três cabeças, uma serpente em vez de cauda e garras afiadas. Sua função era impedir que os vivos entrassem no submundo e que os mortos escapassem.




            

            <p class="mb-2 text-xl">
                Uma das histórias mais conhecidas envolvendo Cerberus é a do décimo segundo trabalho de Hércules (ou Héracles, em grego). Como parte de seus doze trabalhos para redimir-se por ter matado sua família em um momento de loucura, Hércules foi enviado a capturar Cerberus vivo e levá-lo para Euristeu, o rei de Micenas e seu meio-irmão.
                Para conseguir isso, Hércules precisou da ajuda de Atena e Hermes, que o guiaram até o submundo e o instruíram sobre como enfrentar Cerberus. Ele conseguiu subjugar o monstro com sua força sobre-humana, dominando as três cabeças e levando-o à presença de Euristeu.





            </p>
            <p class="mb-2 text-xl">
                Outra história envolvendo Cerberus está ligada à Orfeu, o famoso músico e poeta. Após a morte de sua amada Eurídice, Orfeu desceu ao submundo para tentar trazê-la de volta à vida. Com sua música encantadora, ele conseguiu acalmar Cerberus e abrir caminho até Hades e Perséfone, os governantes do submundo.










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