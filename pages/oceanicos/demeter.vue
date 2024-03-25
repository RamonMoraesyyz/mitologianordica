<template>
  <div
    class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
  >
    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full md:w-1/2">
      <img src="/demeter.png" class="w-full h-screen md:h-auto object-cover" />
    </div>

    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Deméter
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-xl"
          >Deméter, na mitologia grega, é a venerada deusa da agricultura e das
          colheitas, responsável por garantir a fertilidade da terra e o sucesso
          das plantações. Seu mito mais conhecido envolve o rapto de sua filha
          Perséfone por Hades, o que desencadeia a interrupção das estações do
          ano e o declínio das plantações. A busca de Deméter pela filha resulta
          em um acordo que estabelece as estações do ano, refletindo sua
          influência sobre a natureza e o ciclo da vida.
          <p class="mb-2 text-xl">
            Os festivais e rituais dedicados a Deméter eram marcados por
            celebrações durante as épocas de semeadura e colheita, incluindo
            competições atléticas e rituais de fertilidade. Sua importância
            cultural era imensa, pois a agricultura era fundamental para a
            economia e a subsistência da sociedade grega antiga. A deusa era
            invocada não apenas para garantir colheitas abundantes, mas também
            para garantir a estabilidade e a prosperidade da comunidade.
          </p>
          <p class="mb-2 text-xl">
            Deméter era frequentemente representada como uma figura materna,
            segurando símbolos como espigas de trigo ou tochas, transmitindo sua
            associação com a fertilidade e a abundância. Sua imagem simbolizava
            a interconexão entre a natureza e a humanidade, destacando a
            importância do ciclo da vida e da morte na mitologia grega e na
            compreensão da relação entre os seres humanos e o mundo natural.
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