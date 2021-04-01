<template>
  <div id="app">

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <a class="navbar-brand" href="#">Smart Cast</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
          <li><a class="nav-item nav-link" href="#index"><router-link style="text-decoration: none;" to="/">Home</router-link></a></li>
          <li><a class="nav-item nav-link" href="#about">About</a></li>
          <li><a class="nav-item nav-link" href="#services">Services</a></li>
          <li><a class="nav-item nav-link" href="#pricing">Pricing</a></li>
          <li><a class="nav-item nav-link" href="#contact">Contact</a></li>
          <li><button class="btn btn-dark"><router-link style="text-decoration: none;" to="/shop">License keys</router-link></button></li>
    </div>
  </div>
</nav>
    

    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

/* #nav {
  padding: 2rem;
  background-color: rgb(36, 36, 36);
}

#nav a {
  font-weight: bold;
  color: #c2c2c2;
}

#nav a.router-link-exact-active {
  color: rgb(184, 255, 184);
} */
</style>
