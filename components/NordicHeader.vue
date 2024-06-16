<template>
  <div id="app">

    <header class="main-header" style="background-color: black; color: white;">
      <nav class="nav-links">
        
        <div class="dropdown" @mouseenter="dropdownOpenTitans = true" @mouseleave="dropdownOpenTitans = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenTitans">
            <b>Deuses Aesir</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenTitans" aria-labelledby="dropdownMenuTitans">
            <router-link class="dropdown-item" to="/deuses-aesir/odin">Odin</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/thor">Thor</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/loki">Loki</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/frigg">Frigg</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/baldur">Baldur</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/tyr">Tyr</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/heimdall">Heimdall</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/bragi">Bragi</router-link> 
            <router-link class="dropdown-item" to="/deuses-aesir/iduna">Iduna</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/forseti">Forseti</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/hodr">Hodr</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/vidar">Vidar</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/vali">Vali</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/ullr">Ullr</router-link>
            <router-link class="dropdown-item" to="/deuses-aesir/mimir">Mimir</router-link>

            <!-- Adicione outros links dos Titãs aqui -->
          </div>
        </div>
        <div class="dropdown" @mouseenter="dropdownOpenGods = true" @mouseleave="dropdownOpenGods = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenGods">
            <b>Deuses Vanir</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenGods" aria-labelledby="dropdownMenuGods">
            <router-link class="dropdown-item" to="/oceanicos/zeus">Zeus</router-link>
            <router-link class="dropdown-item" to="/oceanicos/hestia">Héstia</router-link>
            <router-link class="dropdown-item" to="/oceanicos/demeter">Démeter</router-link>
            <router-link class="dropdown-item" to="/oceanicos/hera">Hera</router-link>
            <router-link class="dropdown-item" to="/oceanicos/hades">Hades</router-link>
            <router-link class="dropdown-item" to="/oceanicos/poseidon">Poseidon</router-link>
            <div class="dropdown-divider"></div>
            <router-link class="dropdown-item" to="/olimpicos/atena">Atena</router-link>
            <router-link class="dropdown-item" to="/olimpicos/apolo">Apolo</router-link>
            <router-link class="dropdown-item" to="/olimpicos/artemis">Ártemis</router-link>
            <router-link class="dropdown-item" to="/olimpicos/hermes">Hermes</router-link>
            <router-link class="dropdown-item" to="/olimpicos/ares">Ares</router-link>
            <router-link class="dropdown-item" to="/olimpicos/hefesto">Hefesto</router-link>
            <router-link class="dropdown-item" to="/olimpicos/afrodite">Afrodite</router-link>
            <router-link class="dropdown-item" to="/olimpicos/dionisio">Dionísio</router-link>
            <router-link class="dropdown-item" to="/olimpicos/persefone">Perséfone</router-link>
            <router-link class="dropdown-item" to="/olimpicos/eros">Eros</router-link>
          </div>
        </div>
        <b><router-link to="/herois"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenHeroes = true" @mouseleave="dropdownOpenHeroes = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenHeroes">
            <b>Gigantes</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenHeroes" aria-labelledby="dropdownMenuHeroes">
            <router-link class="dropdown-item" to="/herois/heracles">Héracles</router-link>
            <router-link class="dropdown-item" to="/herois/perseu">Perseu</router-link>
            <router-link class="dropdown-item" to="/herois/helena">Helena</router-link>
            <router-link class="dropdown-item" to="/herois/teseu">Teseu</router-link>
            <router-link class="dropdown-item" to="/herois/aquiles">Aquiles</router-link>
            <router-link class="dropdown-item" to="/herois/ulisses">Ulisses</router-link>
            <router-link class="dropdown-item" to="/herois/jasao">Jasão</router-link>
            <router-link class="dropdown-item" to="/herois/belerofonte">Beleforonte</router-link>
            <router-link class="dropdown-item" to="/herois/atalanta">Atalanta</router-link>
            <router-link class="dropdown-item" to="/herois/diomedes">Diomedes</router-link>
            <router-link class="dropdown-item" to="/herois/orfeu">Orfeu</router-link>
            <router-link class="dropdown-item" to="/herois/edipo">Édipo</router-link>
            
            <!-- Adicione outros links dos Heróis aqui -->
          </div>
        </div>
        <b><router-link to="/monstros"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenMonsters = true" @mouseleave="dropdownOpenMonsters = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenMonsters">
            <b>Elfos</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenMonsters" aria-labelledby="dropdownMenuMonsters">
            <router-link class="dropdown-item" to="/monstros/medusa">Medusa</router-link>
            <router-link class="dropdown-item" to="/monstros/cerbero">Cérbero</router-link>
            <router-link class="dropdown-item" to="/monstros/minotauro">Minotauro</router-link>
            <router-link class="dropdown-item" to="/monstros/quimera">Quimera</router-link>
            <router-link class="dropdown-item" to="/monstros/sereia">Sereia</router-link>
            <router-link class="dropdown-item" to="/monstros/hidralerne">Hidra de Lerne</router-link>
            <router-link class="dropdown-item" to="/monstros/ciclope">Ciclopes</router-link>
            <router-link class="dropdown-item" to="/monstros/hecatonquiro">Hecatônquiros</router-link>
            <router-link class="dropdown-item" to="/monstros/grifo">Grifos</router-link>
            <router-link class="dropdown-item" to="/monstros/esfinge">Esfinge</router-link>
            <router-link class="dropdown-item" to="/monstros/harpia">Harpias</router-link>
            <router-link class="dropdown-item" to="/monstros/pegaso">Pégaso</router-link>
            <router-link class="dropdown-item" to="/monstros/centauro">Centauros</router-link>
            <!-- Adicione outros links dos Monstros aqui -->
          </div>
        </div>


        <b><router-link to="/locais"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenLocals = true" @mouseleave="dropdownOpenLocals = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenLocals">
            <b>Anões</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenLocals" aria-labelledby="dropdownMenuLocals">
            <router-link class="dropdown-item" to="/locais/olimpo">Monte Olimpo</router-link>
            <router-link class="dropdown-item" to="/locais/tartaro">Tártaro</router-link>
            <router-link class="dropdown-item" to="/locais/hades">Reino de Hades</router-link>
            <router-link class="dropdown-item" to="/locais/delfos">Oráculo de Delfos</router-link>
            <router-link class="dropdown-item" to="/locais/atenas">Cidade de Atenas</router-link>
            <router-link class="dropdown-item" to="/locais/creta">Ilha de Creta</router-link>
            <router-link class="dropdown-item" to="/locais/delos">Ilha de Delos</router-link>
            <router-link class="dropdown-item" to="/locais/styx">Rio Styx</router-link>
            

          
          </div>
        </div>



        <b><router-link to="/aventuras"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenAdventures = true" @mouseleave="dropdownOpenAdventures = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenAdventures">
            <b>Locais sagrados</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenAdventures" aria-labelledby="dropdownMenuAdventures">
            <router-link class="dropdown-item" to="/aventuras/titanomaquia">Titanomaquia</router-link>
            <router-link class="dropdown-item" to="/aventuras/troia">Guerra de Tróia</router-link>
            <router-link class="dropdown-item" to="/aventuras/iliada">Ilíada</router-link>
            <router-link class="dropdown-item" to="/aventuras/odisseia">Odisséia</router-link>
            <router-link class="dropdown-item" to="/aventuras/dozehercules">12 trabalhos de Hércules</router-link>
            <router-link class="dropdown-item" to="/aventuras/sisifo">O mito de Sísifo</router-link>
            <router-link class="dropdown-item" to="/aventuras/labirinto">Labirinto do Minotauro</router-link>
            <router-link class="dropdown-item" to="/aventuras/argonautas">Jasão e os Argonautas</router-link>
            <!-- Adicione outros links das Aventuras aqui -->
          </div>
        </div>
      </nav>
    </header>
    <!-- Renderiza o conteúdo da página atual -->
    <NuxtPage />
  </div>
</template>

<script>
export default {
  data() {
    return {
      dropdownOpenTitans: false,
      dropdownOpenGods: false,
      dropdownOpenHeroes: false,
      dropdownOpenMonsters: false,
      dropdownOpenLocals: false,
      dropdownOpenAdventures: false,
    };
  },
};
</script>

<style scoped>
.main-header {
  padding: 10px;
 
}

.nav-links {
  display: flex;
  justify-content: space-between; /* Espaçamento entre os elementos */
  align-items: center; /* Centraliza verticalmente os elementos */
}

.dropdown-toggle {
  cursor: pointer;
  padding: 5px 10px;
  font-size: larger;
}

.dropdown-item {
  padding: 5px 10px;
  display: block;
  text-decoration: none;
  color: inherit;
}

.dropdown-menu {
  position: absolute;
  background-color: black; /* Define o fundo branco para o dropdown */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Adiciona uma sombra suave */
  z-index: 1; /* Garante que o dropdown esteja acima dos demais elementos */
}

.dropdown-divider {
  margin: 5px 0;
  border-bottom: 1px solid #ccc;
}

/* Adicionado estilo para tornar o header responsivo */
@media screen and (max-width: 768px) {
  .nav-links {
    flex-direction: column; /* Altera a direção dos elementos para coluna */
  }

  .dropdown {
    margin-bottom: 10px; /* Adiciona espaçamento abaixo do dropdown */
  }
}

/* Espaçamento igual entre todos os botões */
.nav-links .left-buttons > * {
  margin-right: 5px; /* Espaçamento de 5px entre os botões do canto esquerdo */
}

</style>