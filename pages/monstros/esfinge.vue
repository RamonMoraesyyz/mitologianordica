<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/monstros/esfinge.jpeg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Esfinge
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Segundo a mitologia grega, a Esfinge era um ser com corpo de leão, asas de águia e rosto de mulher. Ela habitava as montanhas próximas a Tebas, onde desafiava os viajantes que se aproximavam da cidade com um enigma enigmático. O enigma da Esfinge era o seguinte: "Qual é o ser que tem quatro pés de manhã, dois ao meio-dia e três à tarde?"




            

            <p class="mb-2 text-xl">
                Aqueles que não conseguiam resolver o enigma eram devorados pela Esfinge. A cidade de Tebas estava aterrorizada, pois ninguém conseguia decifrar o enigma e derrotar a criatura. Até que Édipo, o herói lendário e futuro rei de Tebas, apareceu.









            </p>
            <p class="mb-2 text-xl">
                Édipo enfrentou a Esfinge e, confiando em sua inteligência e astúcia, respondeu corretamente ao enigma: "O ser é o homem, que engatinha quando criança, anda ereto na idade adulta e usa uma bengala na velhice". A Esfinge, derrotada pela resposta, se atirou do alto das montanhas e morreu.










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
