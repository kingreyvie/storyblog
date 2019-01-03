<template>
  <nav class="navbar is-danger" role="navigation" aria-label="main navigation">
    <no-ssr>  
      <div class="navbar-brand">
          <nuxt-link to="#">
            <a class="navbar-item">
              <img src="https://bulma.io/images/bulma-logo-white.png" alt="Bulma"/>
            </a>
          </nuxt-link>
          <a class="navbar-burger" role="button" aria-label="menu" aria-expanded="false">
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
      </div>
      <div class="navbar-menu">
          <div class="navbar-start">
              <nuxt-link to="/">
                  <a class="navbar-item has-background-danger">Home</a>
              </nuxt-link>
              <nuxt-link to="/about">
                  <a class="navbar-item has-background-danger ">About Us</a>
              </nuxt-link>
          </div>
          <div class="navbar-end">
          </div>
      </div>
    </no-ssr> 
  </nav>
</template>

<style scoped>
a{
  color: white;
}
.nuxt-link-exact-active a{
color:rgb(11, 65, 106);
border-bottom: 3px solid rgb(11,65,106);
}
</style>
