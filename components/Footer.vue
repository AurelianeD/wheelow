<template>
  <div class="bg-primary_1 pb-5">
    <div class="flex flex-row p-5 justify-between">
      <div>
        <img src="~/assets/img/logo.png" alt="logo-wheelow" class="h-20 w-auto">
      </div>
      <div>
        <img src="~/assets/img/instagram.png" alt="instagram" class="h-7 w-auto mb-2">
        <img src="~/assets/img/facebook.png" alt="facebook" class="h-7 w-auto mt-2">
      </div>
    </div>
    <p class="font-title text-center pb-10">Votre nouvelle ride commence ici !</p>
    <div class="flex justify-center pb-10">
      <Button title="Apple Store" class="bg-white text-primary_1 mr-2"/>
      <Button title="Play Store" class="bg-white text-primary_1 ml-2"/>
    </div>

    <p class="text-center font-title">Fait avec ❤ en partenariat avec <a>MMI Bordeaux️</a></p>
    <p class="text-center font-title"><a>Github</a></p>
  </div>
</template>

<script>
import Button from "~/components/Button";
export default {
  name: "Footer",
  components: {
    Button
  },
  props:['title']
}
</script>

<style scoped>

</style>
