<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/aventuras/labirinto.jpeg" class="w-full h-full object-cover" />
      </div>
         <Script></Script>
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Labirinto do Minotauro
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl">
            
            Teseu era um jovem príncipe ateniense, filho do rei Egeu. Ele cresceu em Tróia, criado por sua mãe Etra, sem saber inicialmente sobre sua linhagem real. Quando Teseu era jovem, uma vez que ele já tinha idade suficiente para buscar aventuras e provar sua coragem, Egeu colocou uma espada e um par de sandálias debaixo de uma pedra grande, dizendo a Teseu que se ele fosse capaz de mover a pedra e pegar os objetos, poderia se revelar como seu filho e herdeiro.




            

            <p class="mb-2 text-xl">
                Depois de muitas aventuras, Teseu finalmente retornou a Atenas e descobriu sua verdadeira identidade. Em uma ocasião, a cidade de Atenas estava sob a obrigação de enviar sete jovens e sete donzelas como tributo para o rei Minos de Creta. Minos exigiu este tributo em retaliação pela morte de seu filho, Androgeu, durante uma competição atlética em Atenas.

                Teseu se ofereceu para ser um dos tributos, com a intenção de enfrentar o temido Minotauro, uma criatura meio-homem, meio-touro, que era mantida no Labirinto de Creta, construído por Dédalo. O Labirinto era um lugar complexo e confuso, do qual ninguém que entrava conseguia escapar.

                Antes de partir, Teseu recebeu a ajuda de Ariadne, filha de Minos, que se apaixonou por ele. Ela deu a Teseu um novelo de fio, conhecido como "Fio de Ariadne", e instruções para amarrá-lo na entrada do labirinto e desenrolá-lo enquanto avançava, para que pudesse encontrar o caminho de volta.


                Quando Teseu entrou no Labirinto, ele seguiu o fio de Ariadne e encontrou o Minotauro. Apesar da ferocidade da criatura, Teseu conseguiu matá-la usando sua espada e escapou do Labirinto seguindo o fio de volta.








            </p>
            <p class="mb-2 text-xl">
                Teseu retornou a Atenas como herói, trazendo consigo não apenas sua própria vida salva, mas também os outros jovens atenienses que estavam destinados a serem sacrificados ao Minotauro.


                A história de Teseu e o Labirinto do Minotauro é uma narrativa de coragem, inteligência e triunfo sobre o mal. Ela simboliza a luta humana contra os desafios aparentemente insuperáveis e a capacidade de superar obstáculos com determinação e estratégia. O mito também destaca o papel fundamental da ajuda de outros, como Ariadne, na superação de desafios difíceis.



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