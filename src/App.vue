<template>
  <div id="app">

    <!-- <a href="license.html" class="get-started-btn scrollto"><router-link to="/shop">License keys</router-link></a>

    <div class="container d-flex align-items-center bg-dark">
      <h1 class="logo mr-auto"><a href="#index">Smart Cast</a></h1>
      <nav class="nav-menu d-none d-lg-block">
        <ul>
          <li class="active"><a href="#index">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#pricing">Pricing</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div> -->

<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Smart Cast</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
          <li><a class="nav-item nav-link" href="#index">Home</a></li>
          <li><a class="nav-item nav-link" href="#about">About</a></li>
          <li><a class="nav-item nav-link" href="#services">Services</a></li>
          <li><a class="nav-item nav-link" href="#pricing">Pricing</a></li>
          <li><a class="nav-item nav-link" href="#contact">Contact</a></li>
          <li><button href="license.html" class="btn-primary bg-light"><router-link to="/shop">License keys</router-link></button></li>
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
