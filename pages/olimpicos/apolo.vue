<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/apollo.jpeg" class="w-full h-full object-cover" />
      </div>
  
      
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
     
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">Apolo</h1>
  
        <div class="mb-4 text-center">
        <label class="mb-2 text-xl">Apolo, filho de Zeus e Leto, é conhecido como o deus grego da luz, da música, da poesia, da profecia, das artes, da medicina e do sol. Ele nasceu na ilha de Delos após sua mãe, Leto, enfrentar dificuldades para dar à luz devido à vingança de Hera. Apolo é lembrado por sua beleza, habilidades musicais e proféticas, bem como por suas aventuras, incluindo a luta contra a serpente Píton para assumir o controle do Oráculo de Delfos. 
          Seus símbolos incluem o sol, a lira, o louro e a flecha, representando suas diversas facetas e influências na mitologia grega.
        <p class="mb-2 text-xl"> Também lembrado por suas relações amorosas e suas interações com mortais e deuses. Seus amores incluem Dafne, uma ninfa transformada em árvore de louro para escapar de seu assédio, e Jacinto, um jovem mortal cuja morte trágica levou à criação da flor de jacinto. Além disso, Apolo é conhecido por suas habilidades curativas, sendo reverenciado como o deus que traz cura e alívio às pessoas enfermas. Sua influência abrange não apenas o mundo divino, 
          mas também a vida cotidiana dos mortais na mitologia grega.
          <br>
          Apolo teve vários filhos notáveis na mitologia grega, incluindo Asclepius, o deus da medicina; Orfeu, um músico e poeta lendário; as sibilas, figuras proféticas associadas a ele; Córiboas, um talentoso músico e poeta; e Aristeu, um deus da agricultura e da apicultura. Cada um desses filhos desempenhou papéis importantes em diferentes aspectos da cultura e da mitologia grega, contribuindo para a riqueza e a complexidade das histórias envolvendo Apolo e sua descendência.

        </p>
        </label>
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