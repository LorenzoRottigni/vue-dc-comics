<template>
    <main class="d-flex flex-column">
        <HeroSection></HeroSection>
        <IconsNav/>
        <Jumbotron/>
    </main>
</template>
<script>
import HeroSection from './../sub-components/HeroSection.vue';
import IconsNav from './../sub-components/IconsNav.vue';
import Jumbotron from './../sub-components/Jumbotron.vue';

export default {
  name: 'Main',
  components: {
    IconsNav,
    Jumbotron,
    HeroSection
  },
  data(){
      return {

      }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../styles/main.scss'
</style>