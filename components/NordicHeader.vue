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
            <router-link class="dropdown-item" to="/deuses-aesir/mimir">Mímir</router-link>

            <!-- Adicione outros links dos Titãs aqui -->
          </div>
        </div>
        <div class="dropdown" @mouseenter="dropdownOpenGods = true" @mouseleave="dropdownOpenGods = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenGods">
            <b>Deuses Vanir</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenGods" aria-labelledby="dropdownMenuGods">
            <router-link class="dropdown-item" to="/deuses-vanir/njord">Njord</router-link>
            <router-link class="dropdown-item" to="/deuses-vanir/frey">Frey</router-link>
            <router-link class="dropdown-item" to="/deuses-vanir/freya">Freya</router-link>
            <router-link class="dropdown-item" to="/deuses-vanir/skadi">Skadi</router-link>
            <router-link class="dropdown-item" to="/deuses-vanir/nerthus">Nerthus</router-link>
            <router-link class="dropdown-item" to="/deuses-vanir/gullveig">Gullveig</router-link>
          </div>
        </div>
        <b><router-link to="/herois"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenHeroes = true" @mouseleave="dropdownOpenHeroes = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenHeroes">
            <b>Gigantes</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenHeroes" aria-labelledby="dropdownMenuHeroes">
            <router-link class="dropdown-item" to="/gigantes/ymir">Ymir</router-link>
            <router-link class="dropdown-item" to="/gigantes/aegir">Aegir</router-link>
            <router-link class="dropdown-item" to="/gigantes/angrboda">Angrboda</router-link>
            <router-link class="dropdown-item" to="/gigantes/baugi">Baugi</router-link>
            <router-link class="dropdown-item" to="/gigantes/belgemir">Belgemir</router-link>
            <router-link class="dropdown-item" to="/gigantes/bestla">Bestla</router-link>
            <router-link class="dropdown-item" to="/gigantes/farbauti">Farbauti</router-link>
            <router-link class="dropdown-item" to="/gigantes/gerd">Gerd</router-link>
            <router-link class="dropdown-item" to="/gigantes/byleistr">Byleistr</router-link>
            <router-link class="dropdown-item" to="/gigantes/gunnlod">Gunnlod</router-link>
            <router-link class="dropdown-item" to="/gigantes/hymir">Hymir</router-link>
            <router-link class="dropdown-item" to="/gigantes/skadi">Skadi</router-link>
            <router-link class="dropdown-item" to="/gigantes/utgard-loki">Utgard-loki</router-link>
            <router-link class="dropdown-item" to="/gigantes/surtur">Surtur</router-link>

            
            <!-- Adicione outros links dos Heróis aqui -->
          </div>
        </div>

        <div class="dropdown" @mouseenter="dropdownOpenHeros = true" @mouseleave="dropdownOpenHeros = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenHeros">
            <b>Heróis</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenHeros" aria-labelledby="dropdownMenuTitans">
            <router-link class="dropdown-item" to="/herois/sigurd">Sigurd</router-link>
            <router-link class="dropdown-item" to="/herois/brynhildr">Brynhildr</router-link>
            <router-link class="dropdown-item" to="/herois/beoulf">Beoulf</router-link>
            <router-link class="dropdown-item" to="/herois/gunnar">Gunnar</router-link>
            <router-link class="dropdown-item" to="/herois/gudrun">Gudrun</router-link>
            <router-link class="dropdown-item" to="/herois/egil">Egil</router-link>
            <router-link class="dropdown-item" to="/herois/helgi">Helgi</router-link>
            <router-link class="dropdown-item" to="/herois/hogni">Hogni</router-link> 
            <router-link class="dropdown-item" to="/herois/hrolf">Hrolf</router-link>
            <router-link class="dropdown-item" to="/herois/ragnar">Ragnar</router-link>
            <router-link class="dropdown-item" to="/herois/bjorn">Bjorn</router-link>
            <router-link class="dropdown-item" to="/herois/elfos">Elfos</router-link>
            <router-link class="dropdown-item" to="/herois/valkirias">Valkirias</router-link>


            <!-- Adicione outros links dos Titãs aqui -->
          </div>
        </div>






        <b><router-link to="/monstros"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenMonsters = true" @mouseleave="dropdownOpenMonsters = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenMonsters">
            <b>Anões</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenMonsters" aria-labelledby="dropdownMenuMonsters">
            <router-link class="dropdown-item" to="/anoes/brokk">Brokk</router-link>
            <router-link class="dropdown-item" to="/anoes/sindri">Sindri</router-link>
            <router-link class="dropdown-item" to="/anoes/dvalin">Dvalin</router-link>
            <router-link class="dropdown-item" to="/anoes/andvari">Andvari</router-link>
            <router-link class="dropdown-item" to="/anoes/alviss">Alviss</router-link>
            <router-link class="dropdown-item" to="/anoes/alfrigg">Alfrigg</router-link>
            <router-link class="dropdown-item" to="/anoes/durin">Durin</router-link>
            <router-link class="dropdown-item" to="/anoes/galar">Galar</router-link>
            <router-link class="dropdown-item" to="/anoes/grer">Grer</router-link>
            <router-link class="dropdown-item" to="/anoes/motsognir">Motsognir</router-link>
            <router-link class="dropdown-item" to="/anoes/berling">Berling</router-link>
            <!-- Adicione outros links dos Monstros aqui -->
          </div>
        </div>


        <b><router-link to="/locais"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenLocals = true" @mouseleave="dropdownOpenLocals = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenLocals">
            <b>Criaturas</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenLocals" aria-labelledby="dropdownMenuLocals">
            <router-link class="dropdown-item" to="/monstros/jormungandr">Jörmungandr</router-link>
            <router-link class="dropdown-item" to="/monstros/fafnir">Fafnir</router-link>
            <router-link class="dropdown-item" to="/monstros/nidhogrr">Níðhöggr</router-link>
            <router-link class="dropdown-item" to="/monstros/fenrir">Fenrir</router-link>
            <router-link class="dropdown-item" to="/monstros/hati">Hati </router-link>
            <router-link class="dropdown-item" to="/monstros/skoll">Skoll </router-link>
            <router-link class="dropdown-item" to="/monstros/hel">Hel </router-link>
            <router-link class="dropdown-item" to="/monstros/garmr">Garmr </router-link>
            <router-link class="dropdown-item" to="/monstros/hraesvelgr"> Hraesvelgr </router-link>
            <router-link class="dropdown-item" to="/monstros/draugr"> Draugr </router-link>
            <router-link class="dropdown-item" to="/monstros/trolls"> Trolls </router-link>
            <router-link class="dropdown-item" to="/monstros/mare"> Mare </router-link>
            <router-link class="dropdown-item" to="/monstros/sleipnir"> Sleipnir </router-link>
            

          
          </div>
        </div>



        <b><router-link to="/aventuras"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenAdventures = true" @mouseleave="dropdownOpenAdventures = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenAdventures">
            <b>Locais</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenAdventures" aria-labelledby="dropdownMenuAdventures">
            <router-link class="dropdown-item" to="/locais/asgard"> Asgard </router-link>
            <router-link class="dropdown-item" to="/locais/midgard"> Midgard </router-link>
            <router-link class="dropdown-item" to="/locais/vanaheim"> Vanaheim </router-link>
            <router-link class="dropdown-item" to="/locais/alfheim"> Alfheim </router-link>
            <router-link class="dropdown-item" to="/locais/jotunheim"> Jotunheim </router-link>
            <router-link class="dropdown-item" to="/locais/muspelheim"> Muspelheim </router-link>
            <router-link class="dropdown-item" to="/locais/helheim"> Helheim </router-link>
            <router-link class="dropdown-item" to="/locais/bifrost"> Bifrost </router-link>
            <router-link class="dropdown-item" to="/locais/yggdrasil"> Yggdrasil </router-link>
            <router-link class="dropdown-item" to="/locais/folkvangr"> Folkvangr </router-link>
            <router-link class="dropdown-item" to="/locais/nidavellir"> Nidavellir </router-link>
            <router-link class="dropdown-item" to="/locais/nilfheim"> Nilfheim </router-link>
            <router-link class="dropdown-item" to="/locais/valhalla"> Valhalla </router-link>

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
      dropdownOpenHeros: false,
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