<template>
  <div id="app">
    <router-view />
    <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>
    </div>
  </div>
</template>

<style>
#app {
  text-align: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  position: absolute;
  left: 0;
  right: 0;
  margin: auto;
  bottom: 0;
  padding: 30px;
  text-align: center;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  margin-inline-end: 10px;
  margin-inline-start: 10px;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
