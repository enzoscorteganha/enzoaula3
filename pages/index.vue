<template>
  <section class="section">
    
    <b-carousel>
      <b-carousel-item>
        <b-image class="image" :src="require('@/assets/violos.png')"/>
      </b-carousel-item>
      
      <b-carousel-item>
        <b-image class="image" 
          :src="require('@/assets/violo.png')"></b-image>
      </b-carousel-item>  
      
      <b-carousel-item>
        <b-image class="image" :src="require('@/assets/guitar.png')"></b-image>
      </b-carousel-item>            
    </b-carousel>


<div class="columns mt-5">
      <div class="column is-3">
        <article class="notification is-white">
          <b-image class="image" :src="require('@/assets/violao.png')"></b-image>
          <p class="title">titulo</p>
          <p class="subtitle">Subtítulo</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
      <div class="column is-3">
        <article class="notification is-white">
          <b-image
            :src="require('@/assets/violao.png')"
          <p class="title">Título</p>
          <p class="subtitle">Subtítulo</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div> 
  <div class="column is-3">
        <article class="notification is-white">
           <b-image
            :src="require('@/assets/violao.png')"
          <p class="title">Título</p>
          <p class="subtitle">Subtítulo</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>     
  <div class="column is-3">
    
        <article class="notification is-white">
          <p class="title">Título</p>
          <p class="subtitle">Subtítulo</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>     
    </div>

   
   
    
  </section>
</template>

