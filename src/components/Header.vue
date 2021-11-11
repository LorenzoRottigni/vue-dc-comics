<template>
    <header>
        <nav class="container-fluid h-100 d-flex px-5 py-3">
                <div class="img-container flex-shrink-0 d-flex align-items-center"><img src="./../assets/dc-logo.png" alt="logo"></div>
                <div class="flex-grow-1 d-flex align-items-center justify-content-center">
                    <ul class="list-unstyled d-flex gap-3 my-0 flex-wrap px-5">
                        <li>CHARACTERS</li>
                        <li>COMICS</li>
                        <li>MOVIES</li>
                        <li class="active">TV</li>
                        <li>GAMES</li>
                        <li>COLLECTIBLES</li>
                        <li>VIDEOS</li>
                        <li>FANS</li>
                        <li>NEWS</li>
                        <li>SHOP</li>
                    </ul>
            </div>
        </nav>
        
    </header>
</template>
<script>
export default {
  name: 'Header',
  data(){
      return {

      }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import './../styles/header';
</style>