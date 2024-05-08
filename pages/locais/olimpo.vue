<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/locais/olimpo.jpeg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Monte Olimpo
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Na mitologia grega, o Monte Olimpo é considerado a morada dos doze principais deuses olímpicos, que formam o panteão mais importante da religião grega antiga.
            Ele é descrito como uma montanha real situada na Tessália, na Grécia continental. No entanto, sua natureza divina o torna inacessível aos mortais comuns.

            O Monte Olimpo é frequentemente retratado como uma montanha majestosa, coberta de neve em seu pico, cercada por nuvens e banhada por uma aura divina.
            Em muitas narrativas mitológicas, é descrito como um local de grande beleza e poder, onde os deuses se reúnem em conselhos e celebrações.




            

            <p class="mb-2 text-xl">
                Os principais habitantes do Monte Olimpo são os doze deuses olímpicos, que compõem o panteão central da mitologia grega.
                Entre os deuses que residem lá estão Zeus (o rei dos deuses e governante do Olimpo), Hera (sua esposa e rainha dos deuses), Atena (deusa da sabedoria e estratégia), Apolo (deus da luz, música e profecia), Artemis (deusa da caça e da lua), entre outros.
                Além dos deuses, também é dito que algumas criaturas mitológicas, como as Ninfas e as Musas, têm conexões especiais com o Monte Olimpo.









            </p>
            <p class="mb-2 text-xl">
                O Monte Olimpo desempenha um papel fundamental na mitologia grega como o centro do universo divino, onde ocorrem muitos dos eventos e conflitos que moldam o mundo dos mortais e dos imortais.
                Ele também tem uma presença significativa na cultura e nas artes gregas, sendo frequentemente representado em pinturas, esculturas, poemas e outras formas de expressão artística.









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