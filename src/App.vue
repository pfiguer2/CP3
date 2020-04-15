<template>
<div id="app">
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/crepes">Crepes</router-link> |
    <router-link to="/flan">Flan</router-link>
  </div>
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

#nav {
  padding: 30px;
  text-decoration: none;
}

#nav a {
  font-weight: bold;
  font-size: 20px;
  color: #2c3e50;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #d96a57;
  text-decoration: none;
}
</style>
