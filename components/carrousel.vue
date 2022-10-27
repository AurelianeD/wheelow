<template>
  <agile>
    <div class="rounded-lg" >
      <img src='~/assets/img/screen/homepage.png' alt="homepage" >
    </div>
    <div>
      <img :src='url2' alt="inscription" >
    </div>
    <div>
      <img :src='url3' alt="itineraire" >
    </div>
    <template v-slot:prevButton >
      <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="py-10">
    </template>
    <template v-slot:nextButton>
      <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="rotate-180 py-10">
    </template>
  </agile>
</template>

<script>
import {VueAgile} from 'vue-agile'
export default {
  name: "Carrousel",
  components:{
    agile: VueAgile
  },
  props:['url1', 'url2', 'url3']
}
</script>

<style scoped>

</style>
