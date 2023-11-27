<template>
  <header>
    <div class="flex justify-evenly items-center text-white bg-gray-600 fixed w-full top-0 left-0 h-24">
      <div>
        <a href="#" rel="internal"><img src="" alt="Logo Header"></a>
      </div>
      <div>
        <nav>
          <ul>
            <a href="https://ddminformatica.com.br/" target="_blank" rel="external" class="hover:text-red-500">Home &nbsp;</a>
            <a href="https://ddminformatica.com.br/servicos/" target="_blank" rel="external" class="hover:text-red-500">Serviços &nbsp;</a>
            <a href="https://ddminformatica.com.br/loja/" target="_blank" rel="external" class="hover:text-red-500">Loja &nbsp;</a>
            <a href="https://ddminformatica.com.br/contato/" target="_blank" rel="external" class="hover:text-red-500">Contato</a>
          </ul>
        </nav>
      </div>
      <div>
        <ul class="bg-red-500 p-2 rounded-lg hover:bg-red-800">
          <a href="#">Minha Conta</a>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>

</script>

<style>
@tailwind base;
@tailwind components;
@font-face {
  font-family: 'Poppins';
  src: url(fonts/Poppins-Light.ttf) format('truetype');
  font-weight: normal;
  font-style: normal;
}
@tailwind utilities;
</style>