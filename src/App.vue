<template>
  <div id="app">
    <Header/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
  import Header from './components/Header'
  import Footer from './components/Footer'

  export default {
    name: 'app',
    components: {Header, Footer}
  }
</script>

<style>
body {
  margin: 0;
  padding: 0;
  text-align: center;
  background-color: rgba(247, 234, 234, 0.863);
  color: rgb(46, 46, 46);
}

a {
  user-select: none;
}
</style>