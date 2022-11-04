<template>
  <nav class="flex justify-between items-center max-w-4xl mx-auto text-white">
    <div class="flex items-center">
      <img class="mr-4" src="icon.png" width="64" height="64" alt="">
      <h1>GQF Protensões</h1>
    </div>
    <ul class="flex space-x-4">
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">Sobre</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/solutions">Soluções</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/clients">Clientes</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/contact">Contato</nuxt-link>
      </li>
    </ul>
  </nav>
</template>