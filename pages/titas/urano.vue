<template>
    <div
      class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden"
    >
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/urano.jpg" class="w-full h-full object-cover" />
      </div>
         
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Urano
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-xl"
            >Urano era filho de Gaia (a terra) e representava o próprio céu na mitologia grega. 
            Ele se tornou o primeiro governante do cosmos e se uniu a Gaia para dar origem aos Titãs, aos Ciclopes e aos Hecatônquiros. 
            No entanto, ele também era conhecido por seu comportamento cruel e tirânico em relação aos filhos, mantendo alguns deles aprisionados dentro de Gaia, o que levou a um conflito entre Urano e seus descendentes.

            

            <p class="mb-2 text-xl">
                Urano era frequentemente retratado como uma figura majestosa e imponente, personificando a abóbada celeste que cobria o mundo. Ele era considerado uma força primordial e poderosa, cuja influência abrangia todos os aspectos do cosmos.
                 Sua conexão com o céu o tornava uma divindade de vastidão e grandeza.
            </p>
            <p class="mb-2 text-xl">
                Urano teve vários filhos, incluindo os Titãs, os Ciclopes e os Hecatônquiros. Alguns de seus filhos notáveis incluem:

                Titãs: Como Cronos, Oceano, Ceos, Reia, Têmis, Mnemosine, entre outros.
                Ciclopes: Gigantes com um olho só no meio da testa, como Brontes, Estéropes e Arges.
                Hecatônquiros: Criaturas com cem braços e cinquenta cabeças, como Coto, Briareu e Gíges.

                O símbolo associado a Urano é o próprio céu, representando a vastidão do universo e sua influência sobre todos os seres e elementos. Ele também é frequentemente simbolizado pela cor azul, que representa o céu aberto, o infinito e a transcendência.

                Além disso, a foice que Cronos usou para castrar Urano também é considerada um símbolo relacionado a Urano, representando o ato de desafiar o poder estabelecido e a ascensão de uma nova ordem na mitologia grega.


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