<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses-aesir/heimdall.jfif" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Heimdall
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-xl">
          Heimdall é filho de nove mães, que são descritas como gigantes ou personificações das ondas do mar. Seu pai é geralmente considerado Odin, o principal deus do panteão nórdico. Essas nove mães são frequentemente interpretadas como as nove irmãs que personificam as ondas, dando a Heimdall uma conexão tanto com o mar quanto com os deuses.


          <p class="mb-2 text-xl">
            Guardiã da Bifrost: Heimdall é o protetor da ponte Bifrost, a única entrada para Asgard. Ele é descrito como estando sempre vigilante, com uma visão aguçada que lhe permite ver a grandes distâncias e uma audição tão sensível que pode ouvir a grama crescer e o som da lã crescendo nas ovelhas.
            Chifre Gjallarhorn: Heimdall possui o chifre Gjallarhorn, que ele soprar para alertar os deuses sobre o início do Ragnarök. O som do Gjallarhorn pode ser ouvido em todos os mundos, convocando os deuses para a batalha final.
            Batalha contra Loki: Durante o Ragnarök, Heimdall enfrenta Loki, o deus trapaceiro, em um combate mortal. Ambos acabam matando um ao outro, destacando a importância de Heimdall como defensor dos deuses até o fim.


          </p>
          <p class="mb-2 text-xl">
            Uma curiosidade interessante sobre Heimdall é sua associação com a humanidade. Segundo algumas lendas, Heimdall desceu à Terra sob o nome de Rígr e visitou três casais humanos, dando origem às três classes sociais da sociedade nórdica antiga: os escravos (Thralls), os homens livres (Karls) e a nobreza (Jarls). Esta história, conhecida como "Rígsþula", enfatiza Heimdall como uma figura de ligação entre os deuses e os humanos.

          </p>
        </label>
      </div>

      <div class="mt-4 text-center">
        <nuxt-link to="/">
          <button class="bg-blue-300 hover:bg-blue-400 text-black text-xl font-bold py-2 px-4 rounded">
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

  
  <style scoped>
  .bg-brown-dark {
    background-color: #211512;
  }
  </style>