<template>
  <div id="app">
    <header class="main-header" style="background-color: black; color: white;">
      <nav class="nav-links">
        
        <div class="dropdown" @mouseenter="dropdownOpenTitans = true" @mouseleave="dropdownOpenTitans = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenTitans">
            <b>Titãs</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenTitans" aria-labelledby="dropdownMenuTitans">
            <router-link class="dropdown-item" to="/titas/urano">Urano</router-link>
            <router-link class="dropdown-item" to="/titas/gaia">Gaia</router-link>
            <div class="dropdown-divider"></div>
            <router-link class="dropdown-item" to="/titas/cronos">Cronos</router-link>
            <router-link class="dropdown-item" to="/titas/reia">Réia</router-link>
            <router-link class="dropdown-item" to="/titas/oceano">Oceano</router-link>
            <router-link class="dropdown-item" to="/titas/ceos">Céos</router-link>
            <router-link class="dropdown-item" to="/titas/febe">Febe</router-link>
            <router-link class="dropdown-item" to="/titas/teia">Téia</router-link>
            <router-link class="dropdown-item" to="/titas/hiperion">Hiperion</router-link>
            <router-link class="dropdown-item" to="/titas/tebas">Tebas</router-link>
            <router-link class="dropdown-item" to="/titas/japeto">Jápeto</router-link>
            <router-link class="dropdown-item" to="/titas/climene">Clímene</router-link>
            <router-link class="dropdown-item" to="/titas/tetis">Tétis</router-link>
            <router-link class="dropdown-item" to="/titas/mnemosine">Mnemosine</router-link>
            <router-link class="dropdown-item" to="/titas/prometeu">Prometeu</router-link>
            <router-link class="dropdown-item" to="/titas/atlas">Atlas</router-link>
            <router-link class="dropdown-item" to="/titas/epimeteu">Epimeteu</router-link>
            <!-- Adicione outros links dos Titãs aqui -->
          </div>
        </div>
        <div class="dropdown" @mouseenter="dropdownOpenGods = true" @mouseleave="dropdownOpenGods = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenGods">
            <b>Deuses</b>
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
          </div>
        </div>
        <b><router-link to="/herois"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenHeroes = true" @mouseleave="dropdownOpenHeroes = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenHeroes">
            <b>Heróis</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenHeroes" aria-labelledby="dropdownMenuHeroes">
            <router-link class="dropdown-item" to="/herois/heracles">Héracles</router-link>
            <router-link class="dropdown-item" to="/herois/perseu">Perseu</router-link>
            <router-link class="dropdown-item" to="/herois/teseu">Teseu</router-link>
            <router-link class="dropdown-item" to="/herois/aquiles">Aquiles</router-link>
            <router-link class="dropdown-item" to="/herois/ulisses">Ulisses</router-link>
            <router-link class="dropdown-item" to="/herois/jasao">Jasão</router-link>
            <router-link class="dropdown-item" to="/herois/belerofonte">Beleforonte</router-link>
            <router-link class="dropdown-item" to="/herois/atalanta">Atalanta</router-link>
            <router-link class="dropdown-item" to="/herois/diomedes">Diomedes</router-link>
            <router-link class="dropdown-item" to="/herois/orfeu">Orfeu</router-link>
            
            <!-- Adicione outros links dos Heróis aqui -->
          </div>
        </div>
        <b><router-link to="/monstros"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenMonsters = true" @mouseleave="dropdownOpenMonsters = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenMonsters">
            <b>Monstros</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenMonsters" aria-labelledby="dropdownMenuMonsters">
            <router-link class="dropdown-item" to="/monstros/medusa">Medusa</router-link>
            <router-link class="dropdown-item" to="/monstros/cerberus">Cérbero</router-link>
            <!-- Adicione outros links dos Monstros aqui -->
          </div>
        </div>
        <b><router-link to="/aventuras"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenAdventures = true" @mouseleave="dropdownOpenAdventures = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenAdventures">
            <b>Aventuras</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenAdventures" aria-labelledby="dropdownMenuAdventures">
            <router-link class="dropdown-item" to="/aventuras/odisseia">Odisseia</router-link>
            <router-link class="dropdown-item" to="/aventuras/jornada-heroi">Jornada do Herói</router-link>
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
  justify-content: space-between; /* Alterado para espaçamento entre os elementos */
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
</style>