<script lang="ts" setup>
import Button from './Button.vue';
</script>

<template>
  <div class="bg-black h-screen sm:h-full">
    <header
      class="bg-purple-600 h-96 rounded-b-3xl flex flex-col justify-center items-center"
    >
      <span class="text-white font-bold text-6xl">The Wall</span> 
      <span class="text-white text-center">
        La única red social centrada en los conciertos que más te gustan
      </span>
    </header>
  
    <main class="flex flex-col justify-center items-center mt-10 gap-3">
      <router-link to="/register">
        <Button text="Crear una cuenta" />
      </router-link>
      <Button text="Entrar con mi cuenta" />
    </main>
  </div>
</template>
