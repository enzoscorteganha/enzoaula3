<template>
  <div>
    <h1 class="title">
      Lista de produtos
    </h1>
<div class="columns">
  <div class="column is-4">
    <h1 class='title is-5'>Filtros:</h1>
    
     <b-field>
            <b-checkbox>Teclas</b-checkbox>
        </b-field>
    <b-field>
            <b-checkbox>Sopro</b-checkbox>
        </b-field>
    <b-field>
            <b-checkbox>Cordas</b-checkbox>
        </b-field>
    <b-field>
            <b-checkbox>Percussão</b-checkbox>
        </b-field>
    
  </div>
  <div class="column is-8">
    <div class="columns">
  <div class="column">
    <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title is-4">onibus lotado</p>
          <p class="subtitle">R$ 2.375.000,00</p>
          <router-link :to="{ path: ' /imagens' }">Exemplo de link</router-link>
        </article>
  </div>
  <div class="column">
     <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title is-3">onibus acre</p>
          <p class="subtitle">R$ 1.300.000,00 </p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
  </div>
  <div class="column">
     <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title is-4">onibus sergipe</p>
          <p class="subtitle">R$ 1.770.000,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
  </div>
  
</div>
    <div class="columns">
  <div class="column">
    <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title is-4">onibus lotado</p>
          <p class="subtitle">R$ 2.375.000,00</p>
          <router-link :to="{ path: ' /imagens' }">Exemplo de link</router-link>
        </article>
  </div>
  <div class="column">
     <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title is-3">onibus acre</p>
          <p class="subtitle">R$ 1.300.000,00 </p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
  </div>
  <div class="column">
     <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title is-4">onibus sergipe</p>
          <p class="subtitle">R$ 1.770.000,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
  </div>
  
</div>
    <div class="columns">
  <div class="column">
    <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title is-4">onibus lotado</p>
          <p class="subtitle">R$ 2.375.000,00</p>
          <router-link :to="{ path: ' /imagens' }">Exemplo de link</router-link>
        </article>
  </div>
  <div class="column">
     <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title is-3">onibus escolar</p>
          <p class="subtitle">R$ 1.300.000,00 </p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
  </div>
  <div class="column">
     <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title is-4">van escolar</p>
          <p class="subtitle">R$ 1.205.000,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
  </div>
  
</div>
  </div>

  
  
</div>

    








    
  </div>
</template>