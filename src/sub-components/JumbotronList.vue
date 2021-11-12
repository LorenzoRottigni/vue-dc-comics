<template>
    <nav>
        <h3>{{listTitle}}</h3>
        <ul class="list-unstyled">
            <li :key="index" v-for="(listItem, index) in listItems">
                {{listItem}}
            </li>
        </ul>
    </nav>
    
</template>

<script>
export default {
  name: 'JumbotronList',
  props: {
      listItems : Array,
      listTitle : String
  },
  data(){
      return {

      }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import './../styles/main';
</style>