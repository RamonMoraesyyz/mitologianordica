<template>
    <div id="app">
      <header class="main-header" style="background-color: black; color: white;">
        <nav class="nav-links">
          <div class="dropdown" @mouseenter="dropdownOpen = true" @mouseleave="dropdownOpen = false">
            <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpen">
              <b style="font-size: larger;">Deuses</b>
            </button>
            <div class="dropdown-menu" v-show="dropdownOpen" aria-labelledby="dropdownMenuButton">
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
          <b><router-link to="/herois">Heróis</router-link></b>
          <b><router-link to="/monstros">Monstros</router-link></b>
          <b><router-link to="/aventuras">Aventuras</router-link></b>
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
        dropdownOpen: false
      };
    }
  }
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