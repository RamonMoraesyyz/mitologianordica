<template>
    <div class="relative bg-brown-dark text-white flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full md:w-1/2">
        <img src="../public/hera.jpg" class="w-full h-screen md:h-auto object-cover" />
      </div>
  
      
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
  
     
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">Hera</h1>
  
        <div class="mb-4 text-center">
        <label class="mb-2"> <p>Hera é uma das principais deusas da mitologia grega, sendo a irmã e esposa de Zeus, o rei dos deuses. Ela é considerada a deusa do casamento, da maternidade e da família, e é frequentemente retratada como uma figura majestosa e poderosa. Hera era filha de Cronos e Reia e, como muitos dos deuses gregos, foi criada no Monte Olimpo.

        Sua união com Zeus foi uma das mais importantes do panteão grego, embora fosse frequentemente marcada por conflitos e ciúmes. De acordo com a mitologia, Zeus a traiu repetidamente com outras deidades e mortais, o que provocou a ira de Hera e resultou em muitos episódios dramáticos.

        Hera era protetora do casamento e da fidelidade conjugal, e punia severamente tanto as amantes de Zeus quanto os filhos ilegítimos que ele gerava. Ela era conhecida por sua natureza ciumenta e vingativa, frequentemente direcionando sua ira contra aqueles que cruzavam seu caminho ou desrespeitavam sua autoridade.

        Além de seu papel como esposa de Zeus, Hera também era uma deusa importante por direito próprio. Ela era considerada a rainha do Olimpo e uma figura materna para muitos dos outros deuses. Era comum invocar sua proteção em questões relacionadas ao casamento, parto e vida familiar.

        Na arte e na literatura grega, Hera é frequentemente retratada como uma mulher majestosa e imponente, vestida com roupas elegantes e adornada com coroas e jóias. Ela é muitas vezes representada segurando um cetro ou uma romã, símbolo de fertilidade e prosperidade.

        Apesar de seu temperamento e das dificuldades em seu relacionamento com Zeus, Hera era reverenciada e adorada em toda a Grécia Antiga, com templos e rituais dedicados a ela em muitas cidades. Ela era uma figura central na religião e na cultura gregas, e sua influência perdurou por séculos após o declínio do mundo antigo.</p> </label>
        </div>

        <div class="mt-4 text-center">
        <nuxt-link to="/">
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-2 px-4 rounded">
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