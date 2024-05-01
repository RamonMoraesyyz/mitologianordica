<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/helena.jpeg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Helena
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Helena era filha de Zeus, o principal deus olímpico, e de Leda, rainha de Esparta. Segundo a mitologia, Zeus apareceu para Leda em forma de cisne, resultando na gestação de dois ovos, dos quais nasceram Helena e seus irmãos Cástor e Pólux, além de Clitemnestra, filha de Leda com seu esposo Tíndaro.

            

            <p class="mb-2 text-xl">
              Helena era conhecida por sua beleza incomparável, o que levou muitos pretendentes a buscar sua mão em casamento. Ela foi prometida e casou-se com Menelau, rei de Esparta, formando assim uma das famílias reais mais poderosas da época.
              O episódio mais famoso de Helena é sua fuga com Páris, príncipe troiano, que a seduziu e a levou consigo para Troia. Esse evento desencadeou a Guerra de Troia, já que Menelau e os gregos consideraram o rapto de Helena um ultraje e uma razão para iniciar uma guerra contra Troia.
              Helena tornou-se uma figura central na Guerra de Troia, sendo desejada por ambos os lados do conflito. Sua beleza e sua presença em Troia foram um dos motivos principais que levaram os gregos a sitiarem a cidade por dez anos.

            </p>
            <p class="mb-2 text-xl">
                Helena teve uma filha com Menelau, chamada Hermione. No entanto, sua paternidade foi questionada devido à longa ausência de Menelau durante a Guerra de Troia.


                Uma curiosidade intrigante sobre Helena é que sua história e sua beleza lendária foram temas recorrentes na arte, na literatura e na cultura ao longo dos séculos. Ela foi representada em inúmeras obras de arte, poemas, peças de teatro e romances, muitas vezes sendo retratada como um símbolo de beleza e desejo, mas também como uma figura complexa e controversa devido aos eventos que desencadeou na mitologia grega.





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