<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses-aesir/iduna.jfif" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Iduna
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-xl">
          Iduna é filha de Ivaldi, um anão renomado por suas habilidades em forjar armas e artefatos mágicos. Ela é casada com Bragi, o deus da poesia, e é frequentemente descrita como uma deusa jovem e bela, refletindo sua associação com a juventude eterna.


          <p class="mb-2 text-xl">
            Guardião das Maçãs da Juventude: Iduna possui maçãs douradas que concedem juventude eterna aos deuses. Sem essas maçãs, os deuses envelheceriam e perderiam sua imortalidade. Iduna guarda essas maçãs em um cofre e as distribui periodicamente para manter os deuses jovens e vigorosos.
            O Rapto de Iduna: Uma das histórias mais famosas envolvendo Iduna é seu rapto pelo gigante Thjazi. Loki, o deus trapaceiro, foi forçado a entregar Iduna a Thjazi para salvar sua própria vida. O rapto de Iduna causou grande tumulto entre os deuses, que começaram a envelhecer rapidamente sem suas maçãs. Eventualmente, Loki resgatou Iduna, transformando-a em uma noz para facilitar sua fuga. Após seu retorno, Iduna restaurou a juventude dos deuses com suas maçãs.
          </p>
          <p class="mb-2 text-xl">
            Uma curiosidade interessante sobre Iduna é sua associação com a renovação e a primavera. Seu nome, Iðunn, pode ser traduzido como "a Rejuvenescedora" ou "a que renova", refletindo seu papel na manutenção da juventude eterna dos deuses. Além disso, algumas interpretações modernas a associam com ciclos de renovação da natureza, simbolizando o rejuvenescimento e o renascimento após o inverno.

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