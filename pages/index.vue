<template>
  <div class="flex items-center justify-center text-blue-700 sm:text-red-400 md:text-yellow-500 lg:text-green-950 lg:hidden h-screen text-4xl cursor-pointer">

   <button @click="handleClick">Entre aqui</button>
  </div>
</template>

<script lang="ts" setup>
function handleClick(event: MouseEvent){
  console.log('click')
}

</script>

<style>

</style>