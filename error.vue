<template>
    <div class="flex items-center justify-center h-screen bg-white">
      <div class="text-center card bg-opacity-80 p-8 rounded-lg">
  


  
        <!-- Conteúdo do erro -->
        <div class="relative z-10 text-center mt-10">
          <p v-if="error" class="text-7xl font-bold text-black">{{ error.statusCode }}</p>
          <p class="mt-7 text-2xl text-black font-bold">
            Página não encontrada <br>
            
          </p>
        </div>
  
        <p v-if="error" class="mt-7 text-xl text-black font-bold">{{ error.message }}</p>
        <br>
        <button @click="handleClearError" class="bg-zinc-300 hover:bg-zinc-400 text-black text-xl font-bold py-2 px-4 rounded">
          Retornar à página inicial
        </button>
      </div>
    </div>
  </template>
  
  <script setup>
  
  const props = defineProps(['error']);

  const handleClearError = () => clearError ({ redirect: '/' })
  
  </script>