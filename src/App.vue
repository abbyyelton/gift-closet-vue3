<template>
  <div>
    <nav>
      <router-link to="/">Gifts</router-link> |
      <router-link to="/closet">Closet</router-link> |
      <router-link to="/people">People</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #FFFFFF;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #00323f;
}

nav a.router-link-exact-active {
  color: #E43681;
}

body {
  background-image: url('@/assets/background.jpg');
  background-size: cover;
}
</style>
