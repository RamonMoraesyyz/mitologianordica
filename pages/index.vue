<template>
  <head>
    <link rel="icon" type="image/png" href="/static/helmet.png">
  </head>
  <div class="relative flex items-center justify-center min-h-screen bg-cover bg-center" style="background-image: url('/welcome.jpeg');">
    <div class="text-center p-8 text-white max-w-3xl mx-auto bg-black bg-opacity-50 rounded-lg">
      <h1 class="text-7xl mb-8 drop-shadow-lg">Mitologia Nórdica</h1>
      <p class="text-2xl drop-shadow-lg leading-relaxed">
        A mitologia nórdica, com suas ricas narrativas e personagens como Odin, Thor e Loki, possui uma importância profunda na compreensão das tradições e valores das antigas sociedades escandinavas. O estudo desses mitos oferece insights valiosos sobre como esses povos viam o mundo, suas crenças sobre a natureza, os deuses, a vida e a morte.
        <br/><br/>
        Na sociedade moderna, a influência da mitologia nórdica pode ser vista em vários aspectos do nosso dia a dia. Muitos nomes de dias da semana, por exemplo, são derivados dos deuses nórdicos, como Thursday (quinta-feira) de Thor e Wednesday (quarta-feira) de Odin. Além disso, a mitologia nórdica inspira arte, música e até mesmo a cultura popular, contribuindo para uma identidade cultural rica e diversificada.
      </p>
    </div>
  </div>
</template>

<style scoped>
.bg-cover {
  background-size: cover;
}

.bg-center {
  background-position: center;
}

.drop-shadow-lg {
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
}

.bg-opacity-50 {
  background-color: rgba(0, 0, 0, 0.5);
}

.leading-relaxed {
  line-height: 1.75;
}

.rounded-lg {
  border-radius: 0.5rem;
}
</style>
