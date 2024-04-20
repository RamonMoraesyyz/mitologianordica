<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/cronos.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Cronos
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Cronos era filho de Urano (o céu) e Gaia (a terra). Ele era o líder dos Titãs e governava durante a chamada era de ouro, um período de grande prosperidade e harmonia na mitologia grega. No entanto, ele também é conhecido por um ato terrível que moldou sua história: ele castrou seu pai, Urano, com uma foice fornecida por Gaia, como parte de uma trama para derrubar Urano do poder.

            Após isso, Cronos se tornou o governante dos céus, e sua irmã e esposa, Reia, se tornou sua rainha. No entanto, ele temia uma profecia que dizia que um de seus filhos o derrubaria do trono, então ele começou a devorar seus filhos assim que nasciam.

            

            <p class="mb-2 text-xl">
                Cronos é frequentemente retratado como um líder poderoso, mas também como alguém que é governado pelo medo e pela paranoia. Sua decisão de devorar seus filhos é um aspecto central de sua caracterização, mostrando sua crueldade e o medo que o consumia.

                Ele é muitas vezes descrito como um Titã imponente, com uma presença dominante e uma aura de autoridade e medo ao seu redor.
            </p>
            <p class="mb-2 text-xl">
                Cronos teve vários filhos com Reia, mas ele os devorava assim que nasciam, como parte de sua tentativa de evitar a profecia que dizia que um deles o destronaria. 
                Alguns dos filhos de Cronos que foram devorados incluem Héstia, Deméter, Hera, Hades e Poseidon. No entanto, Reia conseguiu salvar Zeus, que mais tarde se tornou o responsável por derrubar Cronos e libertar seus irmãos.

                O símbolo mais associado a Cronos é a foice, que ele usou para castrar Urano e assumir o controle dos céus. Essa foice também é frequentemente usada para simbolizar o poder de Cronos sobre o tempo, já que ele é muitas vezes identificado com o deus do tempo na mitologia grega.

                Além disso, Cronos também é associado ao conceito de ciclo temporal, representando o ciclo de vida e morte, renovação e transformação.
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