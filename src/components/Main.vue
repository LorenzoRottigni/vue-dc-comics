<template>
    <main>
        <DarkContentSection/>
        <IconsNav/>
    </main>
</template>
<script>

import DarkContentSection from './../sub-components/DarkContentSection.vue';
import IconsNav from './../sub-components/IconsNav.vue';

export default {
  name: 'Main',
  components: {
    DarkContentSection,
    IconsNav
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