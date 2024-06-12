<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/titas/tebas.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Tebas
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Tébas era filho de Urano (o céu) e Gaia (a terra), fazendo parte da segunda geração de titãs na mitologia grega. 
            Ele fazia parte da linhagem titânica que desafiou o poder de Urano e, posteriormente, de seu filho Cronos.

            <p class="mb-2 text-xl">
                As características específicas de Tébas não são tão detalhadas nas mitologias clássicas quanto as de outros titãs. No entanto, como um titã, ele era visto como uma poderosa entidade primordial associada aos elementos cósmicos e à ordem divina.
                Filhos e Descendência: Na mitologia grega, não há muitas referências diretas aos filhos de Tébas. 
                Seu papel principal costuma estar relacionado à sua participação na genealogia dos deuses e titãs.
                Simbologia e Importância: Como muitos titãs, Tébas representa forças primordiais e aspectos fundamentais do cosmos. Sua simbologia está associada à estruturação do mundo e à transição de poder entre as gerações divinas, marcando momentos cruciais na mitologia grega.
 
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