<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/aventuras/iliada.jpeg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Ilíada
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            A "Ilíada" é uma obra extensa e complexa, então vou resumir a história de forma abrangente, destacando os principais eventos e personagens. Aqui está a história da "Ilíada":

            
            A guerra é desencadeada devido ao rapto de Helena, esposa de Menelau, rei de Esparta, por Páris, príncipe de Troia.
            Os gregos, liderados por Agamenon, irmão de Menelau, reúnem uma grande coalizão para atacar Troia e resgatar Helena.
            
            A história começa no décimo ano da Guerra de Troia, quando Aquiles, o grande herói grego, entra em conflito com Agamenon por causa de uma disputa de prêmios.
            Aquiles se recusa a lutar e retira-se da batalha, levando sua mãe, Tétis, a pedir aos deuses que ajudem os troianos para humilhar os gregos e, assim, fazer com que Aquiles volte à guerra.




            

            <p class="mb-2 text-xl">
                A guerra é retratada em uma série de batalhas entre os gregos (aqueus) e os troianos, liderados por Heitor.
                Destacam-se duelos entre heróis, como Aquiles e Heitor, Pátroclo (amigo de Aquiles) e Heitor, entre outros.
                A morte de Pátroclo pelas mãos de Heitor leva Aquiles a voltar à batalha, motivado pela vingança.
                Aquiles mata Heitor em combate e desonra seu corpo, mas depois concorda em devolvê-lo ao rei troiano Príamo, que vem pessoalmente buscar o corpo de seu filho.









            </p>
            <p class="mb-2 text-xl">
                A "Ilíada" termina com os funerais de Heitor e Pátroclo, simbolizando o luto e a honra dos heróis caídos.
                Embora não seja retratado na "Ilíada", o cavalo de Troia, um estratagema que leva à queda de Troia, é um evento posterior à história contada na obra.

                A "Ilíada" aborda temas como a fúria (ira) de Aquiles, a glória dos heróis, a intervenção dos deuses, o destino humano e os horrores da guerra.
                Ela é considerada uma reflexão profunda sobre a condição humana, os conflitos éticos e as consequências da busca por poder e vingança.









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