<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/dog.jpeg">
    <welcome-header></welcome-header>
    <main-page></main-page>
    <footer-page></footer-page>

  </div>
</template>

<script>

import WelcomeHeader from './components/WelcomeHeader'
import MainPage from './components/MainPage'
import FooterPage from './components/FooterPage'

export default {
  name: 'App',
  components: {
      WelcomeHeader,
      MainPage,
      FooterPage,
      
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
