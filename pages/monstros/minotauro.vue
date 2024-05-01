<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/minotauro.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Minotauro
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >O Minotauro era uma criatura com corpo de homem e cabeça de touro, nascida como resultado de uma maldição divina e de um desejo imprudente. O Rei Minos, buscando fortalecer seu poder e prestígio, pediu a Posídon, o deus do mar, que enviasse um touro branco como símbolo de sua aprovação. Minos prometeu sacrificar o touro em honra a Posídon, mas quando viu a majestade do animal, decidiu mantê-lo e sacrificar um outro touro em seu lugar.




            

            <p class="mb-2 text-xl">
                Posídon, furioso com a quebra da promessa, fez com que Pasífae se apaixonasse pelo touro branco, resultando na concepção do Minotauro. A criatura nasceu, e por sua natureza feroz e monstruosa, foi aprisionada no labirinto construído por Dédalo, um famoso arquiteto e inventor.
                O labirinto era um complexo intrincado de corredores e salas, projetado para confundir e aprisionar qualquer um que entrasse nele. O Minotauro foi colocado lá para ser alimentado com sacrifícios humanos enviados de Atenas como parte de um acordo de paz entre Creta e Atenas.






            </p>
            <p class="mb-2 text-xl">
                A lenda de Teseu e o Minotauro é uma das histórias mais famosas envolvendo essa criatura. Teseu, um herói ateniense, decidiu se voluntariar para enfrentar o Minotauro e libertar Atenas do tributo de sangue. Com a ajuda de Ariadne, filha de Minos e Pasífae, Teseu recebeu um novelo de lã que ele usou para marcar o caminho de volta no labirinto depois de matar o Minotauro.
                Teseu entrou no labirinto, enfrentou o Minotauro e o derrotou com sua coragem e habilidade. Seguindo o fio de Ariadne, conseguiu encontrar o caminho de volta e escapar do labirinto junto com os outros jovens atenienses que estavam destinados a serem sacrificados.











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