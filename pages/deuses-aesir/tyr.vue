<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses-aesir/tyr.jfif" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Tyr
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-xl">
          Tyr é filho de Odin, o deus supremo, embora algumas fontes sugiram que ele possa ser filho do gigante Hymir. A dualidade de suas origens reflete a complexidade de seu caráter, sendo uma figura central tanto na guerra quanto na justiça.


          <p class="mb-2 text-xl">
            O feito mais notável de Tyr é sua participação na captura do lobo gigante Fenrir, filho de Loki. Fenrir estava se tornando uma ameaça crescente aos deuses, e eles decidiram prendê-lo com uma corrente mágica chamada Gleipnir. Fenrir, desconfiado, concordou em ser amarrado somente se um dos deuses colocasse a mão em sua boca como garantia de boa fé. Tyr, mostrando sua coragem e compromisso com a segurança dos deuses, voluntariamente colocou sua mão na boca de Fenrir. Quando Fenrir percebeu que estava preso e não poderia escapar, ele mordeu a mão de Tyr, arrancando-a. Esse sacrifício fez de Tyr um símbolo de coragem e abnegação.

          </p>
          <p class="mb-2 text-xl">
            Uma curiosidade interessante sobre Tyr é sua associação com a terça-feira. Em inglês, o nome do dia da semana "Tuesday" é derivado de "Tiw's day," onde "Tiw" é uma forma antiga do nome Tyr. Isso mostra a influência e a importância do deus na cultura nórdica e germânica.

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
