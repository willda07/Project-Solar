<template>
  <div id="app">
    <router-view/>
    <div id="nav">
      <router-link to="/">Home</router-link>
      <router-link to="/Map">Map</router-link>
      <router-link to="/statistics">Statistics</router-link>
      <router-link to="/policies">Policies</router-link>
      <router-link to="/info">Info</router-link>
    </div>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  margin-top: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    border: 5px solid green;
    border-radius: 5px;
    padding: 40px;
    padding-top: 20px;
    padding-bottom: 50px;
    text-decoration: none;
    margin: 10px;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
