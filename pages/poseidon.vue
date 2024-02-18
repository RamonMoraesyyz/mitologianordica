<template>
    <div class="relative bg-brown-dark text-white flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2 flex items-center justify-center">
        <img src="../public/poseidon.jpg" class="w-full h-screen md:h-auto object-cover" />
      </div>
  
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">Poseidon</h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2">
            <p>Poseidon é uma das divindades mais importantes na mitologia grega, sendo conhecido como o deus dos mares, das tempestades, dos terremotos e dos cavalos. Ele é frequentemente retratado como uma figura poderosa e imponente, associada ao vasto e imprevisível oceano. Poseidon era filho dos titãs Cronos e Reia, e irmão de Zeus e Hades, fazendo parte da segunda geração de deuses olímpicos.

            Como senhor dos mares, Poseidon tinha controle sobre as águas e era frequentemente retratado carregando um tridente, seu símbolo distintivo e uma arma temida. Ele era adorado por marinheiros e pescadores, que o invocavam para garantir viagens seguras e boas pescarias, mas também temido por sua capacidade de provocar tempestades e maremotos.

            Além de seu domínio sobre os oceanos, Poseidon também era conhecido por sua rivalidade com seu irmão Zeus. Ambos disputaram o domínio do Monte Olimpo e do mundo dos mortais, e Poseidon frequentemente desafiava a autoridade de Zeus, resultando em conflitos e disputas entre os deuses.

            Poseidon teve vários filhos e filhas em suas muitas aventuras amorosas, incluindo criaturas mitológicas como o cavalo alado Pégaso e o ciclope Polifemo. Seus descendentes também incluem heróis como Teseu, que foi criado em parte pelo deus do mar.

            Na arte e na literatura grega, Poseidon é frequentemente retratado como um homem imponente e barbudo, vestindo uma túnica e segurando seu tridente. Ele é muitas vezes representado cavalgando pelas ondas em um carro puxado por cavalos marinhos.

            Apesar de sua personalidade tempestuosa e suas frequentes disputas com outros deuses, Poseidon era uma figura reverenciada na Grécia Antiga, com templos e festivais dedicados a ele em várias cidades costeiras. Sua influência perdurou por séculos após o declínio da cultura grega, e ele continua sendo uma das figuras mais emblemáticas e poderosas da mitologia.</p>
          </label>
        </div>
  
        <div class="mt-4 text-center">
          <nuxt-link to="/">
            <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-2 px-4 rounded">
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