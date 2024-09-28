<template>
  <h1>404</h1>
  <p>Page not found</p>

  <div>
    <nav>
      <router-link to="/">Go to home page</router-link>
    </nav>
  <router-view/>
  </div>
</template>

<style scoped>

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #0b8a47;
  text-decoration: none;
  padding: 10px;
  border-radius: 4px;
}

nav a.router-link-exact-active {
  color: white;
  background: #42b983;
}
</style>