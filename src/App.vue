<template>
  <div id="d-flex flex-column">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>

import Header from './components/Header'
import Main from './components/Main'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">

</style>
