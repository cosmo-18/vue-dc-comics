<template>
            <div class="fumetto" >
            <img class="fum" :src="datiComic.thumb" alt="">
            <div class="bord">
                <h5>{{datiComic.series}}</h5>
            </div>
          </div>
</template>

<script>

export default {
  props: {

    datiComic: Object
  }
}
</script>

<style lang="scss">


</style>