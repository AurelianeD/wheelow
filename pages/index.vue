<template>
  <div>
    <div class="p-5 bg-white w-full fixed z-10 flex flex-row justify-between">
      <img src="~/assets/img/logo.png" alt="logo-wheelow" class="h-10 w-auto">
      <h1 class=" font-title text-primary_1 text-3xl">WHEELOW</h1>
    </div>
    <div class="px-5 bg-white">
      <div class="flex flex-col justify-center pt-40 pb-10 md:flex-row">
        <div class="w-fit md:w-50 md:flex md:flex-col md:justify-center md:items-center">
          <h1 class="font-title text-center text-3xl md:text-5xl">Votre nouvelle application pour rider un max</h1>
          <p class="text-end font-text md:pt-10">by <span class="line-through font-bold">V3</span></p>
          <p class="text-end font-title text-primary_1 text-xl md:text-3xl">Wheelow</p>
        </div>
        <img src="~/assets/img/bike2.png" alt="image vélo" class=" my-10 md:pl-10">
      </div>
      <div class="flex flex-col items-center">
        <Button class="my-10" title="Commencer à rider"/>
      </div>
      <h2 class="font-title text-3xl text-center py-10">Ce qui change</h2>
      <p class="font-title text-center text-primary_2 text-2xl py-20">Un design tout neuf, plus accessible</p>
<!--      <agile infinite>-->
<!--        <div>-->
<!--          <img src='~/assets/img/screen/homepage.png' alt="homepage" class="pl-[50%]  h-96">-->
<!--        </div>-->
<!--        <div>-->
<!--          <img src='~/assets/img/screen/station.png' alt="station" class="pl-[50%]  h-96">-->
<!--        </div>-->
<!--        <template v-slot:prevButton class="">-->
<!--          <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="pb-10">-->
<!--        </template>-->
<!--        <template v-slot:nextButton>-->
<!--          <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="rotate-180 pt-10">-->
<!--        </template>-->
<!--      </agile>-->
      <div class="md:flex md:flex-row md:justify-around">
        <div class="flex justify-center py-10">
          <img src='~/assets/img/screen/homepage.png' alt="homepage" class="h-96 border-2 border-primary_1 p-2 rounded-lg">
        </div>
        <div class="flex justify-center pb-10 md:py-10">
          <img src='~/assets/img/screen/station.png' alt="station" class="h-96 border-2 border-primary_1 p-2 rounded-lg">
        </div>
      </div>


      <p class="font-title text-center text-primary_2 text-2xl py-20">Organiser simplement vos trajet du quotidien</p>
<!--      <agile>-->
<!--        <div class="rounded-lg" >-->
<!--          <img src='~/assets/img/screen/trajet.svg' alt="trajet" class="h-50">-->
<!--        </div>-->
<!--        <div>-->
<!--          <img src='~/assets/img/screen/vélo.svg' alt="vue velo" >-->
<!--        </div>-->
<!--        <div>-->
<!--          <img src='~/assets/img/screen/pieton.svg' alt="vue pieton" >-->
<!--        </div>-->
<!--        <template v-slot:prevButton >-->
<!--          <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="pb-10">-->
<!--        </template>-->
<!--        <template v-slot:nextButton>-->
<!--          <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="rotate-180 pt-10">-->
<!--        </template>-->
<!--      </agile>-->
      <div class="md:flex md:flex-row md:justify-around">
        <div class="flex justify-center py-10">
          <img src='~/assets/img/screen/trajet.svg' alt="trajet" class="h-96 border-2 border-primary_1 p-2 rounded-lg">
        </div>
        <div class="flex justify-center pb-10 md:py-10">
          <img src='~/assets/img/screen/vélo.svg' alt="velo" class="h-96 border-2 border-primary_1 p-2 rounded-lg">
        </div>
        <div class="flex justify-center pb-10 md:py-10">
          <img src='~/assets/img/screen/pieton.svg' alt="pieton" class="h-96 border-2 border-primary_1 p-2 rounded-lg">
        </div>
      </div>
      <p class="font-title text-center text-primary_2 text-2xl py-20">Ne vous faites plus avoir, reservez votre vélo avant de partir</p>
<!--      <agile>-->
<!--        <div class="rounded-lg" >-->
<!--          <img src='~/assets/img/screen/resa.svg' alt="reservation" >-->
<!--        </div>-->
<!--        <div>-->
<!--          <img src='~/assets/img/screen/resa2.svg' alt="reservation" >-->
<!--        </div>-->
<!--        <template v-slot:prevButton >-->
<!--          <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="py-10">-->
<!--        </template>-->
<!--        <template v-slot:nextButton>-->
<!--          <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="rotate-180 py-10">-->
<!--        </template>-->
<!--      </agile>-->
      <div class="md:flex md:flex-row md:justify-around">
        <div class="flex justify-center py-10">
          <img src='~/assets/img/screen/resa.svg' alt="reservation" class="h-96 border-2 border-primary_1 p-2 rounded-lg">
        </div>
        <div class="flex justify-center pb-10 md:py-10">
          <img src='~/assets/img/screen/resa2.svg' alt="reservation" class="h-64 border-2 border-primary_1 p-2 rounded-lg">
        </div>
        <div class="flex justify-center pb-10 md:py-10">
          <img src='~/assets/img/screen/resa3.svg' alt="reservation" class="h-72 border-2 border-primary_1 p-2 rounded-lg">
        </div>
      </div>

      <p class="font-title text-center text-primary_2 text-2xl py-20">Faites du vélo, gagner des points...</p>
<!--      <agile>-->
<!--        <div class="rounded-lg" >-->
<!--          <img src='~/assets/img/screen/1point.svg' alt="1 point" >-->
<!--        </div>-->
<!--        <div>-->
<!--          <img src='~/assets/img/screen/2point.svg' alt="2 points" >-->
<!--        </div>-->
<!--        <div>-->
<!--          <img src='~/assets/img/screen/3point.svg' alt="3 points" >-->
<!--        </div>-->
<!--        <template v-slot:prevButton >-->
<!--          <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="py-10">-->
<!--        </template>-->
<!--        <template v-slot:nextButton>-->
<!--          <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="rotate-180 py-10">-->
<!--        </template>-->
<!--      </agile>    -->
      <div class="md:flex md:flex-row md:justify-around">
        <div class="flex justify-center py-10">
          <img src='~/assets/img/screen/1point.svg' alt="1 point" class="h-40 border-2 border-primary_1 p-2 rounded-lg">
        </div>
        <div class="flex justify-center pb-10 md:py-10">
          <img src='~/assets/img/screen/2point.svg' alt="2 points" class="h-44 border-2 border-primary_1 p-2 rounded-lg">
        </div>
        <div class="flex justify-center pb-20 md:py-10">
          <img src='~/assets/img/screen/3point.svg' alt="3 points" class="h-52 border-2 border-primary_1 p-2 rounded-lg">
        </div>
      </div>
      <h2 class="font-title text-3xl text-center">Et devenez le roi de la station</h2>
      <div class="md:flex md:justify-center">
        <img src="~/assets/img/bike.png" alt="vélo">
      </div>
      <h2 class="font-title text-3xl text-center py-20">Alors prêt à rider ?</h2>

    </div>
    <Footer />
  </div>
</template>

<script>
import Button from '../components/Button.vue'
import footer from "../components/Footer.vue";
import {VueAgile} from 'vue-agile'

export default {
  name: 'IndexPage',
  components: {
    Button,
    footer,
    agile: VueAgile
  },
  props: ['title']
}
</script>
