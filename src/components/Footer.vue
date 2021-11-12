<template>
    <footer class="d-flex align-items-center">
        <div class="container-fluid">
            <div class="row px">
                <div class="col-6 offset-1 px-5">
                    <button class="btn btn-outline-primary">
                        SIGN-UP NOW!
                    </button>
                </div>
                <div class="col-5 d-flex gap-3 justify-content-end align-items-center px-5">
                    <h4>FOLLOW US</h4>
                    <ul class="list-unstyled d-flex gap-3">
                        <li><img src="./../assets/footer-facebook.png" alt="facebook icon"></li>
                        <li><img src="./../assets/footer-periscope.png" alt="periscope icon"></li>
                        <li><img src="./../assets/footer-pinterest.png" alt="pinteres icon"></li>
                        <li><img src="./../assets/footer-twitter.png" alt="twitter icon"></li>
                        <li><img src="./../assets/footer-youtube.png" alt="youtube icon"></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'Footer',
  data(){
      return {

      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import './../styles/footer.scss'
</style>