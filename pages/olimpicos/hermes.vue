<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/hermes.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Hermes
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Hermes é uma figura importante na mitologia grega, sendo conhecido como o mensageiro dos deuses, o protetor dos viajantes, dos ladrões e dos comerciantes. 

            É filho de Zeus, e de Maia, uma das Plêiades. Ele nasceu em uma caverna no Monte Cilene, na Arcádia.

            

            <p class="mb-2 text-xl">
                Hermes é famoso por sua habilidade como mensageiro divino. Ele era encarregado de transmitir mensagens entre os deuses e os humanos, bem como de guiar as almas dos mortos para o submundo.
                Hermes era venerado como protetor dos viajantes, garantindo-lhes segurança em suas jornadas. Ele também era considerado o padroeiro dos ladrões, usando sua astúcia para realizar travessuras e escapar de situações perigosas.
                Hermes era associado ao comércio e aos negócios, sendo reverenciado pelos comerciantes em busca de sucesso e lucro.
            </p>
            <p class="mb-2 text-xl">
                O símbolo mais conhecido de Hermes é o caduceu, um bastão entrelaçado por duas serpentes, que simboliza sua habilidade como mensageiro e negociador.
                Hermes também é retratado com as talaria, sandálias aladas que lhe conferiam velocidade e agilidade.
               

                Teve vários filhos na mitologia grega, incluindo:
                Pan: O deus dos bosques, dos pastores e dos rebanhos, conhecido por sua aparência meio humana e meio caprina.
                Autólico: Um habilidoso ladrão e trapaceiro, considerado o pai da astúcia e da destreza
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