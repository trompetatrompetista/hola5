<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>|
    <router-link to="/sistema">sistema</router-link>
  </nav>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  opacity:0.9;
  color: #2c3e50;
}

nav {
  background-color: aqua;
  opacity:0.6;
  padding: 30px;

  a {
    font-weight: bold;
    color: #04101d;

    &.router-link-exact-active {
      color: #26703a;
    }
  }
}
</style>
