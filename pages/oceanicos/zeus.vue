<template>
  <div
    class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
  >
    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full md:w-1/2">
      <img
        src="/zeus2.png"
        class="w-full h-auto md:h-full object-cover transform scale-70"
      />
    </div>

    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
      <h1 class="text-2xl md:text-4xl font-bold mb-4 md:mb-10 mt-1 text-center">
        Zeus
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-xl"
          >Zeus, o principal deus do panteão grego, é reconhecido como o
          soberano do céu e governante dos deuses e dos homens e tem como
          símbolo o raio. Filho de Cronos e Réia, ele liderou a rebelião contra
          seu pai e os Titãs na Titanomaquia, emergindo vitorioso. Representado
          como um homem maduro de barba e postura majestosa, Zeus é
          frequentemente retratado empunhando um raio, símbolo de seu poder e
          autoridade.
          <p class="mb-2 text-xl">
            Como deus do trovão e do céu, ele controlava os elementos naturais e
            garantia a ordem cósmica, intervindo para assegurar que a justiça
            fosse cumprida. Conhecido por seus numerosos amores e aventuras,
            Zeus tinha uma inclinação por se relacionar com mortais, resultando
            em uma infinidade de filhos semideuses ou divinos, como Atena,
            Hermes e Perseu, entre muitos outros.
          </p>
          <p class="mb-2 text-xl">
            Além disso, Zeus era mestre dos disfarces, frequentemente assumindo
            diferentes formas para seduzir suas amantes ou para interagir com
            humanos, o que lhe permitia escapar de situações complicadas e
            cumprir seus desejos e objetivos divinos.
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