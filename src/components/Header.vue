<script lang="ts" setup>
import Button from './Button.vue';
</script>

<template>
  <div
    class="bg-purple-600 h-96 rounded-b-3xl flex flex-col justify-center items-center"
  >
    <span class="text-white font-bold text-6xl">The Wall</span> 
    <span class="text-white text-center">
      La única red social centrada en los conciertos que más te gustan
    </span>
  </div>

  <div class="flex flex-col h-full justify-center items-center mt-10 gap-3">
    <Button text="Crear una cuenta" />
    <Button text="Entrar con mi cuenta" />
  </div>
</template>
