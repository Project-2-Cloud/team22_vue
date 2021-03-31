<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/prices">Prices</router-link> |
      <router-link to="/shop">Licence Shop</router-link>
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
  color: #2c3e50;
}

#nav {
  padding: 2rem;
  background-color: rgb(36, 36, 36);
}

#nav a {
  font-weight: bold;
  color: #c2c2c2;
}

#nav a.router-link-exact-active {
  color: rgb(184, 255, 184);
}
</style>
