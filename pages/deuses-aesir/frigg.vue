<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses-aesir/frigg.jfif" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Frigg
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          Frigg é filha de Fjörgyn (também conhecida como Jörð), a deusa da terra, e de um pai desconhecido. Como esposa de Odin, ela ocupa um lugar de grande importância entre os deuses Aesir e é a rainha de Asgard.

          Frigg é mãe de vários filhos, sendo o mais famoso Baldur. Outros filhos incluem:
          Höðr: Um deus cego que, sob a manipulação de Loki, acidentalmente matou seu irmão Baldur.
          Hermod: Um deus menos conhecido que tentou resgatar Baldur do reino dos mortos.
          Bragi (em algumas versões): Deus da poesia e da eloquência.

          <p class="mb-2 text-l">
            Frigg é conhecida por sua sabedoria e capacidade de prever o futuro. Apesar de ter esse poder, ela raramente revela o que sabe, mantendo seus conhecimentos para si mesma.
            Um dos feitos mais conhecidos de Frigg está relacionado à morte de seu filho Baldur. Após Baldur ter sonhos premonitórios sobre sua própria morte, Frigg fez todos os seres vivos e objetos jurarem não causar dano a Baldur. No entanto, ela negligenciou o visco, acreditando ser inofensivo. Loki usou um galho de visco para fabricar uma flecha, que foi usada por Höðr para matar Baldur.

          </p>
          <p class="mb-2 text-l">
            Frigg é frequentemente associada ao dia da semana sexta-feira, conhecido em inglês como "Friday," derivado de "Frigg’s day." Essa associação é refletida em várias culturas germânicas e anglo-saxãs. Ela é muitas vezes comparada à deusa Freyja, embora as duas sejam distintas, algumas vezes suas histórias e atributos se sobrepõem.
            Frigg tem sua própria sala no palácio de Asgard, chamada Fensalir, que é descrita como um lugar de grande beleza e serenidade. Ela é uma figura central em várias lendas nórdicas e é reverenciada por sua sabedoria, amor e devoção à sua família.

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
