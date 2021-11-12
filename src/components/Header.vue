<template>
    <header>
        <nav class="container-fluid h-100 d-flex px-5 py-3">
                <div class="img-container flex-shrink-0 d-flex align-items-center"><img src="./../assets/dc-logo.png" alt="logo"></div>
                <div class="flex-grow-1 d-flex align-items-center justify-content-end">
                    <ul class="list-unstyled d-none d-lg-flex gap-3 my-0 px-2 justify-content-end">
                        <li>CHARACTERS</li>
                        <li>COMICS</li>
                        <li>MOVIES</li>
                        <li>TV</li>
                        <li>GAMES</li>
                        <li class="active">COLLECTIBLES</li>
                        <li>VIDEOS</li>
                        <li>FANS</li>
                        <li>NEWS</li>
                        <li>SHOP</li>
                    </ul>
                </div>
                <div class="pos-f-t d-lg-none">
                    <div class="collapse" id="navbarToggleExternalContent">
                        <div class="bg-dark p-4">
                        <h4 class="text-white">Collapsed content</h4>
                        <span class="text-muted">Toggleable via the navbar brand.</span>
                        </div>
                    </div>
                    <nav class="navbar navbar-dark bg-dark">
                        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                        </button>
                    </nav>
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