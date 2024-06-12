<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

<!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses-aesir/odin.jpg" class="w-full h-full object-cover" />
      </div>
     
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-blue-200">
          <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Odin
        </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          

          <p>Odin é filho do gigante Borr e da deusa Bestla. Ele é neto de Búri, o primeiro ser divino criado a partir do gelo primordial de Ginnungagap, e irmão dos deuses Vili e Vé. Junto com seus irmãos, Odin matou o gigante primordial Ymir e usou seu corpo para criar o mundo.</p>

          <p>Odin teve vários filhos com diferentes deusas e mulheres. Entre os mais notáveis estão: Thor: Filho de Odin e da deusa Jörð (a personificação da Terra), Thor é o deus do trovão, conhecido por sua força, coragem e pelo martelo Mjölnir. Baldur: Filho de Odin e da deusa Frigg, Baldur é o deus da luz, pureza e beleza. Sua morte é um evento crucial que prenuncia o Ragnarök, o fim do mundo. Víðarr: Outro filho de Odin, conhecido como o deus da vingança, que está destinado a vingar a morte de seu pai durante o Ragnarök. Höðr: Filho de Odin e Frigg, Höðr é o deus cego que, enganado por Loki, mata seu irmão Baldur.</p>

          <p>Feitos: Criação do Mundo: Odin, junto com seus irmãos Vili e Vé, criou o mundo a partir do corpo do gigante Ymir. Sacrifício pelo Conhecimento: Em sua busca por sabedoria, Odin se sacrificou pendurando-se na árvore Yggdrasil por nove dias e nove noites, sem comida nem água, ferido pela própria lança. Este sacrifício lhe concedeu o conhecimento das runas. Poço de Mimir: Odin também sacrificou um de seus olhos para beber da fonte de Mímir, ganhando sabedoria e entendimento profundos. Domínio da Magia Seidr: Odin é mestre da magia Seidr, uma forma de magia associada à adivinhação e mudança do destino.</p>

          <p>Uma curiosidade interessante sobre Odin é que ele possui dois corvos, Huginn e Muninn, que voam ao redor do mundo e retornam para trazer informações ao deus. Huginn representa o pensamento, enquanto Muninn representa a memória. Esses corvos são uma extensão de sua busca incessante por conhecimento e vigilância constante sobre o mundo.</p>
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
:root {
  --header-height: 64px; /* Ajuste esse valor conforme necessário */
}

.bg-brown-dark {
  background-color: #211512;
}


.fixed-image {
  position: relative;
}

.text-container {
  margin-left: auto;
}
</style>
