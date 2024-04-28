<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/aquiles.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Aquiles
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Aquiles é filho de Peleu, rei dos Mírmidons, e da deusa do mar Tétis. Sua mãe tentou torná-lo imortal mergulhando-o nas águas do rio Estige, segurando-o pelo calcanhar. No entanto, o calcanhar por onde Tétis o segurava não foi tocado pela água do rio, tornando-o vulnerável nessa área, o que se tornaria sua famosa fraqueza.
             Desde jovem, Aquiles mostrou sinais de grandeza e destreza nas artes da guerra. Ele foi educado pelo centauro Quíron, que o ensinou a lutar, caçar e tocar música. Sua lendária habilidade como guerreiro logo se tornou evidente, destacando-o entre os heróis de sua época.


            

            <p class="mb-2 text-xl">
                Aquiles é mais conhecido por sua participação na Guerra de Troia, onde sua raiva e coragem marcaram muitos eventos cruciais. Seu papel na guerra foi central, especialmente após a morte de Pátroclo, seu amigo íntimo e companheiro de batalha.
                Um de seus feitos mais lembrados é a batalha com Heitor, o príncipe troiano. Aquiles vingou a morte de Pátroclo matando Heitor em um combate individual, um evento emocionalmente poderoso na narrativa da Guerra de Troia.


            </p>
            <p class="mb-2 text-xl">
                Aquiles é tradicionalmente creditado com um filho, Neoptólemo, também conhecido como Pirro. Neoptólemo se destacou como um guerreiro valente, seguindo os passos de seu pai na mitologia grega. No entanto, existem variações nas histórias sobre a descendência de Aquiles em diferentes fontes mitológicas.
                Uma curiosidade fascinante sobre Aquiles está relacionada à sua conexão com a mitologia e a história posterior. Acredita-se que seu famoso calcanhar vulnerável, por onde sua mãe Tétis o segurou ao mergulhá-lo no rio Estige para torná-lo invulnerável, tenha dado origem à expressão "calcanhar de Aquiles". Essa expressão é usada até os dias de hoje para descrever uma fraqueza ou ponto vulnerável em uma pessoa ou sistema, mesmo que seja altamente eficaz em outros aspectos. Essa associação entre Aquiles e sua fraqueza simbólica se tornou parte integrante do vocabulário e da cultura em geral, mostrando como a mitologia antiga continua a influenciar nosso entendimento e linguagem moderna.








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