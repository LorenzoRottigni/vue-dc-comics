<template>
    <div class="jumbotron jumbotron-fluid">
        <div class="container">
            <div class="row">
                <div class="col-6 offset-1  d-flex gap-4 py-3">
                    <div>
                        <JumbotronList 
                        listTitle="DC COMICS"
                        :listItems="[
                            'Characters',
                            'Comics',
                            'Movies',
                            'TV',
                            'Games',
                            'Videos',
                            'News',
                        ]"/>
                        <JumbotronList 
                        listTitle="Shop"
                        :listItems="[
                            'Shop DC',
                            'Shop DC collectibles'
                        ]"/>
                    </div>
                    
                    <JumbotronList 
                    listTitle="DC"
                    :listItems="[
                        'Term Of Use',
                        'Privacy Policy (New)',
                        'Ad Choises',
                        'Advertising',
                        'Jobs',
                        'Subscriptions',
                        'Talent Workshops',
                        'CPSC Certificates',
                        'Ratings',
                        'Shop Help',
                        'Contact Us'
                    ]"/>
                    <JumbotronList 
                    listTitle="SITES"
                    :listItems="[
                        'DC',
                        'MAD Magazine',
                        'DC Kids',
                        'DC Universe',
                        'DC Power visa',
                    ]"/>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import JumbotronList from './JumbotronList.vue'
export default {
  name: 'Jumbotron',
  data(){
      return {

      }
  },
  components:{
      JumbotronList
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import './../styles/main';
</style>