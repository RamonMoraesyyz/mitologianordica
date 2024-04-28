<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/herois/atalanta.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Atalanta
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Atalanta era filha de Iasus, rei de Arcádia, e sua mãe era frequentemente identificada como Clímene. Ela foi abandonada logo após o nascimento, mas foi criada por uma ursa e, posteriormente, por caçadores. Sua história é marcada por sua notável destreza como caçadora e guerreira.

            

            <p class="mb-2 text-xl">
              Atalanta era famosa por sua habilidade com o arco e flecha, sendo uma das melhores caçadoras de sua época.
              Ela foi uma das heroínas que participou da Caçada de Calidão, uma expedição liderada por Meleagro para matar o javali gigante de Calidão.
              Um dos episódios mais conhecidos envolvendo Atalanta é a corrida de Pélias. Ela prometeu se casar com quem conseguisse vencê-la em uma corrida, mas aqueles que perdiam eram mortos por ela. Hipômenes, com a ajuda de Afrodite, venceu a corrida ao lançar maçãs douradas para distrair Atalanta.
              Atalanta também participou da famosa expedição dos Argonautas em busca do Velocino de Ouro, onde mostrou suas habilidades como guerreira e se destacou entre os membros da tripulação.

            </p>
            <p class="mb-2 text-xl">
              Atalanta teve um filho chamado Partênio ou Parthenopaios, cujo pai foi variadamente atribuído a Mélia, Andrômeda ou Édipo, dependendo da versão da lenda.

              Uma curiosidade interessante sobre Atalanta é que sua história aborda temas como igualdade de gênero, força feminina e a capacidade das mulheres de se destacarem em atividades tradicionalmente associadas aos homens, como a caça e a guerra. Ela é frequentemente vista como um símbolo de independência e habilidade feminina na mitologia grega.







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