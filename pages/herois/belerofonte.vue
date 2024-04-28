<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/belerofonte.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Beleforonte
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Belerofonte, também conhecido como Bellerophon em inglês, é um herói da mitologia grega conhecido por suas habilidades montando Pégaso e por suas batalhas contra criaturas temíveis. Sua história é bastante rica e cheia de feitos impressionantes.


            Belerofonte era filho de Glauco, rei de Corinto, e era neto de Sísifo, conhecido por seus castigos eternos nos subterrâneos. Sua mãe era Eurínome ou Eurimedusa, dependendo da versão da história. Ele ficou conhecido por suas proezas heróicas, principalmente relacionadas à sua habilidade de domar e voar em Pégaso, o famoso cavalo alado.

            

            <p class="mb-2 text-xl">
                Um de seus feitos mais famosos foi sua luta contra a Quimera, uma criatura mitológica com corpo de leão, cabeça de cabra e cauda de serpente. A Quimera era temida por sua ferocidade e era considerada invencível, mas Belerofonte, montado em Pégaso e com a ajuda de uma lança especial dada por Atena, conseguiu derrotá-la.

                Além disso, Belerofonte também foi enviado para lutar contra tribos inimigas pelo rei Ióbates de Lícia. Em vez de matá-lo, o rei enviou-o para enfrentar tarefas quase impossíveis, como matar a Quimera, na esperança de que Belerofonte não sobrevivesse. No entanto, Belerofonte conseguiu superar cada desafio com a ajuda de Pégaso.

            </p>
            <p class="mb-2 text-xl">
                Belerofonte teve filhos, embora nem todos sejam amplamente mencionados na mitologia. Seus filhos mais conhecidos são Isandro, Hipôloco e Laodâmia.

                Uma curiosidade interessante sobre Belerofonte é que, apesar de seus feitos heroicos, ele também cometeu um grande erro ao tentar voar até o Olimpo montado em Pégaso. Zeus, o deus dos deuses, furioso com sua arrogância, enviou uma mosca para picar Pégaso, fazendo Belerofonte cair e ficar cego, terminando seus dias como um mendigo solitário e desamparado.







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