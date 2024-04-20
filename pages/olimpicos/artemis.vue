<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/artemis.jpg" class="w-full h-full object-cover" />
      </div>
  
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Ártemis
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Artemis é uma deusa da mitologia grega associada à caça, à natureza selvagem e à fertilidade. 
            Ela é frequentemente retratada como uma jovem caçadora com arco e flechas, acompanhada por animais selvagens,
             como veados e ursos.

            <p class="mb-2 text-xl">
                Artemis é filha de Zeus, e de Leto, uma titã. 
                Sua mãe teve dificuldades para dar à luz devido à perseguição de Hera, esposa de Zeus, que estava com ciúmes. 
                No entanto, Artemis e seu irmão gêmeo Apolo nasceram em Delos, uma ilha flutuante onde Leto encontrou refúgio.

                Desde tenra idade, Artemis demonstrou habilidades excepcionais na caça, sendo frequentemente retratada com um arco e flechas. 
                Ela é reverenciada como a deusa protetora dos animais selvagens, sendo implacável contra aqueles que os maltratam.
                Artemis é uma das deusas virgens do Olimpo, dedicada à castidade e à preservação da sua pureza. Ela valoriza sua independência e liberdade, rejeitando frequentemente avanços amorosos.
            </p>
            <p class="mb-2 text-xl">
                Arco e Flecha: Seu símbolo mais icônico é o arco e flecha, representando sua habilidade na caça e sua conexão com a natureza selvagem.
                Artemis é associada a animais selvagens, como o veado (símbolo da sua habilidade na caça), o urso e o cão de caça. Ela também é retratada com uma coroa de flores ou ramos, simbolizando sua ligação com a natureza e a fertilidade.
                Apesar de ser virgem, é frequentemente acompanhada por um séquito de ninfas, suas companheiras na caça e na vida selvagem. Ela também é mencionada como protetora das mulheres durante o parto e das jovens donzelas.
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