<template>
  <img alt="Vue logo" src="./assets/telecharger.png" />
  <nav>
    <router-link to="/">Films</router-link>
  </nav>
  <router-view />
</template>

<style lang="scss" scoped>



nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
