<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses-aesir/loki.jfif" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Loki
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          Loki é filho dos gigantes Fárbauti e Laufey, e tem dois irmãos, Helblindi e Býleistr. Embora sua origem seja gigante, ele vive entre os deuses de Asgard e é considerado parte do panteão nórdico. 
          Ele é tanto um ajudante quanto um antagonista dos deuses, especialmente de Odin e Thor. Uma das suas histórias mais conhecidas é quando ele corta o cabelo de Sif, esposa de Thor, e depois tem que compensar o erro, resultando na criação de várias armas e objetos mágicos, incluindo o martelo de Thor, Mjölnir.
          <p class="mb-2 text-l">
            Loki tem uma descendência notável e diversa. Com a gigante Angrboda, ele teve três filhos monstruosos:

          Fenrir: Um lobo gigante destinado a matar Odin durante o Ragnarök.
          Jörmungandr: A serpente de Midgard, que circunda o mundo e está destinada a lutar contra Thor no fim dos tempos.
          Hel: A deusa que governa o reino dos mortos, também chamado Helheim.
          Além disso, Loki é pai de Sleipnir, o cavalo de oito patas de Odin, que nasceu de uma relação inusitada em que Loki se transformou em uma égua e foi impregnado pelo garanhão Svaðilfari.
          </p>
          <p class="mb-2 text-l">
            A criação de Mjölnir: Como mencionado, Loki foi responsável indiretamente pela criação do martelo de Thor, um dos artefatos mais poderosos da mitologia nórdica.
            Enganar Hoder: Loki engana o deus cego Hoder para que este mate seu irmão Balder com um ramo de visco, a única coisa capaz de ferir Balder.
            A ligação com o Ragnarök: Loki é um dos principais responsáveis pelo início do Ragnarök, o fim do mundo na mitologia nórdica. Ele será libertado de suas amarras e liderará os gigantes e criaturas contra os deuses de Asgard.
            Curiosidade
            Uma curiosidade interessante sobre Loki é sua habilidade de mudar de forma e gênero. Em várias histórias, ele se transforma em diferentes animais e até em seres humanos do sexo oposto. Essa fluidez de forma e identidade reflete seu caráter enganador e adaptável, permitindo-lhe escapar de situações complicadas e causar confusão entre os deuses e os mortais.
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
