<template>
    <main class="d-flex flex-column">
        <DarkContentSection/>
        <IconsNav/>
        <Jumbotron class="flex-grow-1"/>
    </main>
</template>
<script>
import DarkContentSection from './../sub-components/DarkContentSection.vue';
import IconsNav from './../sub-components/IconsNav.vue';
import Jumbotron from './../sub-components/Jumbotron.vue';

export default {
  name: 'Main',
  components: {
    DarkContentSection,
    IconsNav,
    Jumbotron
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