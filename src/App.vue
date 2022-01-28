<template>
  <div id="app">
   <div id="nav" class="container">
  <b-navbar toggleable="lg" type="dark" variant="">
    <b-navbar-brand href="#"><img src=".//assets/imgs/logo.png" class="logo"></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ms-auto">
        <b-nav-item href=""><router-link to="/">Home</router-link> |</b-nav-item>
        <b-nav-item href=""><router-link to="/contact">Contactus</router-link></b-nav-item>
        <b-nav-item href=""><router-link to="/about">About</router-link></b-nav-item>
        <b-nav-item href=""><router-link to="/service">Service</router-link></b-nav-item>
      </b-navbar-nav>

    
    </b-collapse>
  </b-navbar>
   </div>
  
    
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* color: #2c3e50; */
  /* color: var(--main-color) */
}

.logo{

  height: 8vh;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
