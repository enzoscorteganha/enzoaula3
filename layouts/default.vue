   <template>
  <div class="container is-fluid">

    <b-navbar >
        <template #brand>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                <img
                    src="https://raw.githubusercontent.com/buefy/buefy/dev/static/img/buefy-logo.png"
                    alt="Lightweight UI components for Vue.js based on Bulma"
                >
            </b-navbar-item>
        </template>
        <template #start>
            <b-navbar-item tag="router-link" :to="{ path: '/' }">
                Home
            </b-navbar-item>
          
          <b-navbar-item tag="router-link" :to="{ path: '/produtos' }">
                Produtos
            </b-navbar-item>
          
          
            <b-navbar-item tag="router-link" :to="{ path: '/carrinho' }">
                Carrinho
            </b-navbar-item>
        </template>
      

        <template #end>
            <b-navbar-item tag="div">
                <div class="buttons">
                    <a class="button is-white">
                        <strong>Cadastre-se</strong>
                    </a>
                    <a class="button is-white">
                        Login
                    </a>
                </div>
            </b-navbar-item>
        </template>
    </b-navbar>

    <Nuxt/>

    <footer class="footer">
      <div class="content has-text-centered">
        <p>
          <strong>Nuxt exemplo</strong> by Robson Luz. 
          <a target="_blank" href="https://fae.edu">FAE Centro Universitário</a>
        </p>
      </div>
    </footer>      
    
  </div>
</template>

