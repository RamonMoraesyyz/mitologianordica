<template>
  <div
    class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
  >
    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses/atena.jpeg" class="w-full h-full object-cover" />
    </div>

    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Atena
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-xl"
          >Atena é considerada filha de Zeus, o rei dos deuses, embora sua
          origem divina seja um tanto complexa na mitologia grega. Segundo uma
          versão, Atena nasceu diretamente da cabeça de Zeus, após ele ter
          engolido Métis, a titânide da prudência e da sabedoria, para evitar o
          nascimento de um filho mais poderoso que ele.
          <p class="mb-2 text-xl">
            Atena é uma das divindades mais complexas e reverenciadas do panteão
            olímpico. Ela é conhecida principalmente como a deusa da sabedoria,
            da inteligência estratégica e da civilização. Representa a mente
            racional, a prudência e a capacidade de tomar decisões sábias e
            ponderadas. Além disso, é uma deusa guerreira, mas seu aspecto
            militar difere de Ares, o deus da violência e do caos, pois
            personifica a guerra justa, o planejamento estratégico e a
            habilidade tática. Atena é também a padroeira das artes, da
            arquitetura, da ciência, da justiça e da democracia, inspirando
            criatividade, excelência intelectual e progresso humano. A coruja e
            a oliveira são os principais símbolos associados a Atena. A coruja é
            considerada um animal sagrado da deusa, representando sabedoria e
            visão noturna. Já a oliveira é o símbolo mais conhecido de Atena,
            representando paz, prosperidade e fertilidade. Acredita-se que ela
            presenteou os atenienses com uma oliveira, tornando-se assim a
            padroeira da cidade de Atenas.
          </p>
          <p class="mb-2 text-xl">
            Uma das histórias mais famosas envolvendo Atena é sua disputa com
            Poseidon pelo patronato de Atenas. Atena venceu ao presentear os
            atenienses com uma oliveira, enquanto Poseidon ofereceu um cavalo.
            Além disso, ela desempenhou um papel crucial na mitologia grega,
            auxiliando heróis como Perseu e Ulisses em suas jornadas. Atena é
            frequentemente retratada como uma figura poderosa e sábia,
            reverenciada não apenas pelos gregos, mas também por muitas outras
            culturas ao longo da história.
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