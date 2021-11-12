<template>
    <div>
        <section class="hero-section">
        
        </section>
        <div class="series-container py-5 px-3 d-flex flex-wrap justify-content-center gap-5">
            <SerieCard :key="index" v-for="(serie, index) in seriesArray"
            :cardData="{
                price : serie.price,
                serie : serie.series,
                thumb : serie.thumb,
                type : serie.type
            }"/>
            <div class="d-flex align-items-center w-100">
                <button class="btn btn-lg btn-outline-primary d-block mx-auto">LOAD MORE</button>
            </div>
            
        </div>  
        
    </div>
    
</template>
<script>
import JSONdata from './../data/dc-comics.json';
import SerieCard from './../sub-components/SerieCard.vue'
export default {
  name: 'HeroSection',
  components: {
      SerieCard
  },
  data(){
      return {
          seriesArray : JSONdata
      }
  },
  mounted(){
      console.log(this.seriesArray)
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import './../styles/main'
</style>