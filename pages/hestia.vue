<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2">
        <img src="/hestia.jpg" class="w-full h-screen md:h-auto object-cover" />
      </div>
  
      
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
     
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">Héstia</h1>
  
        <div class="mb-4 text-center">
        <label class="mb-2 text-xl">Héstia, uma das divindades olímpicas da mitologia grega, personifica a essência do lar, da família e da lareira sagrada. Como guardiã do lar, ela simboliza a união familiar e a harmonia, sendo reverenciada por sua natureza dócil e gentil. Sua lareira é o centro de cada casa grega, onde as famílias se reúnem para oferecerem suas orações e sacrifícios, fortalecendo os laços familiares e promovendo a estabilidade.
        <p class="mb-2 text-xl">Apesar de ser uma das doze divindades olímpicas, Héstia raramente figura em histórias mitológicas. No entanto, sua importância na vida cotidiana dos antigos gregos era inegável. O culto a Héstia era vital na Grécia Antiga, com sacrifícios frequentes oferecidos em seu nome no início e no final de refeições, e suas bênçãos eram invocadas para proteger o lar e a família.</p>
        <p class="mb-2 text-xl">Os templos de Héstia, conhecidos como "Hestiaia", eram locais sagrados de refúgio e santuário, muitas vezes localizados no centro das cidades. Héstia, com sua decisão de permanecer virgem e dedicada ao seu papel como guardiã do lar, personifica pureza e estabilidade, refletindo os valores fundamentais da sociedade grega antiga em relação à família e ao lar.</p> </label>
        </div>

        <div class="mt-4 text-center">
        <nuxt-link to="/">
          <button class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded">
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