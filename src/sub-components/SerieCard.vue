<template>
    <div class="serie-card d-flex flex-column flex-wrap">
        <img :src="cardData.thumb" alt="serie image" class="d-block mx-auto">
        <h3 class="pt-3">{{cardData.serie}}</h3>
        <h4>{{cardData.price}}</h4>
        <h5>{{cardData.type}}</h5>
    </div> 
</template>
<script>
    export default {
        name : 'SerieCard',
        props : {
            cardData : Object
        }
    }
    
</script>
<style scoped lang="scss">
    @import './../styles/main';
</style>
