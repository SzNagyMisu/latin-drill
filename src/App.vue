<template>
  <div id="nav">
    <router-link :to="{ name: 'Home' }">Pagina principalis</router-link> |
    <router-link :to="{ name: 'Declensions' }">Declinationes</router-link> |
    <router-link :to="{ name: 'Conjugations' }">Coniugationes</router-link>
  </div>
  <router-view/>
</template>
