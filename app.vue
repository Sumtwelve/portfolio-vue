<template>
  <header>
    <AppHeader />
  </header>
  <body>
    <NuxtPage id="nuxt-page" />
  </body>
  <footer>
    &copy; 2024 Sumtwelve // Noah Nielsen
  </footer>
</template>

<script>
import AppHeader from './components/AppHeader'
</script>

<style>
body {
  padding: 0;
  margin: 0;
}

footer {
  position: fixed;
  bottom: 0;
  color: whitesmoke;
  background-color: #09006C;
  text-align: center;
  width: 100%;
  padding: 10px 0;
  margin-top: 50px;
  z-index: 5;
}

#nuxt-page {
  padding: 0 30px;
  text-align: center;
}

</style>