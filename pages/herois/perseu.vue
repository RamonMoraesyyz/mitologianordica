<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/perseu.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Perseu
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Perseu era filho de Zeus, o rei dos deuses, e Danae, uma princesa mortal. Sua avó, a rainha Acrísio, havia sido informada por um oráculo de que seu neto a mataria. Para evitar esse destino, Acrísio aprisionou Danae em uma torre de bronze. No entanto, Zeus conseguiu entrar na torre na forma de uma chuva de ouro e concebeu Perseu com Danae.

            Quando Perseu nasceu, Acrísio, temendo a profecia, colocou mãe e filho em um baú e os lançou ao mar. Eles foram salvos por pescadores e acabaram em uma terra chamada Serifos, governada pelo tirano Polidectes. Perseu cresceu sob os cuidados de Dictis, um pescador generoso.
            

            <p class="mb-2 text-xl">
                A história de Perseu ganha destaque quando Polidectes se apaixona por Danae, mas Perseu se opõe ao seu assédio. Polidectes, então, arma um plano para se livrar de Perseu, pedindo-lhe a cabeça da Medusa, uma górgona cujo olhar transformava as pessoas em pedra. Com a ajuda dos deuses Hermes e Atena, Perseu embarca em uma jornada perigosa.

                Durante sua busca pela Medusa, Perseu recebe presentes divinos, como a espada de Zeus, um escudo polido como um espelho e sandálias aladas. Ele enfrenta muitos desafios, incluindo as Graças e as Górgonas, até finalmente encontrar a Medusa e derrotá-la cortando-lhe a cabeça enquanto olhava apenas através do reflexo em seu escudo.
            </p>
            <p class="mb-2 text-xl">
                Após essa conquista, Perseu enfrenta outras aventuras, como salvar Andrômeda de um monstro marinho e participar de vários feitos heroicos. Ele se casa com Andrômeda e tem vários filhos, incluindo Electrião e Alcámenes.






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