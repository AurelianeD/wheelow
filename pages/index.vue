<template>
  <div class="px-5 bg-white">
    <div class="py-5 bg-white fixed w-screen z-10">
      <img src="~/assets/img/logo.png" alt="logo-wheelow" class="h-10 w-auto">
      <h1 class="text-end font-title text-primary_1">WHEELOW</h1>
    </div>
    <div class="flex flex-col justify-center pt-40 pb-10 md:flex-row">
      <div class="w-fit">
        <h1 class="font-title text-center text-3xl md:text-5xl">Votre nouvelle application pour rider un max</h1>
        <p class="text-end font-text">by <span class="line-through">V3</span></p>
        <p class="text-end font-title text-primary_1 text-xl">Wheelow</p>
      </div>
      <img src="~/assets/img/bike2.png" alt="image vélo" class=" my-10">
    </div>
    <div class="flex flex-col items-center">
      <Button class="my-10" title="Commencer à rider"/>
    </div>
    <h2 class="font-title text-3xl text-center py-10">Ce qui change</h2>
    <p class="font-title text-center">Un design tout neuf, plus accessible</p>
    <agile>
      <div class="rounded-lg" >
        <img src='~/assets/img/screen/homepage.png' alt="homepage" >
      </div>
      <div>
        <img src='~/assets/img/screen/inscription.png' alt="inscription" >
      </div>
      <div>
        <img src='~/assets/img/screen/itineraire.png' alt="itineraire" >
      </div>
      <template v-slot:prevButton >
        <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="py-10">
      </template>
      <template v-slot:nextButton>
        <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="rotate-180 py-10">
      </template>
    </agile>
    <p class="font-title text-center">Organiser simplement vos trajet du quotidien</p>
    <agile>
      <div class="rounded-lg" >
        <img src='~/assets/img/screen/trajet.svg' alt="trajet" >
      </div>
      <div>
        <img src='~/assets/img/screen/vélo.svg' alt="vue velo" >
      </div>
      <div>
        <img src='~/assets/img/screen/pieton.svg' alt="vue pieton" >
      </div>
      <template v-slot:prevButton >
        <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="py-10">
      </template>
      <template v-slot:nextButton>
        <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="rotate-180 py-10">
      </template>
    </agile>
    <p class="font-title text-center">Ne vous faites plus avoir, reservez votre vélo avant de partir</p>
    <agile>
      <div class="rounded-lg" >
        <img src='~/assets/img/screen/resa.svg' alt="reservation" >
      </div>
      <div>
        <img src='~/assets/img/screen/resa2.svg' alt="reservation" >
      </div>
      <template v-slot:prevButton >
        <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="py-10">
      </template>
      <template v-slot:nextButton>
        <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="rotate-180 py-10">
      </template>
    </agile>
    <p class="font-title text-center">Faites du vélo, gagner des points...</p>
    <agile>
      <div class="rounded-lg" >
        <img src='~/assets/img/screen/1point.svg' alt="1 point" >
      </div>
      <div>
        <img src='~/assets/img/screen/2point.svg' alt="2 points" >
      </div>
      <div>
        <img src='~/assets/img/screen/3point.svg' alt="3 points" >
      </div>
      <template v-slot:prevButton >
        <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="py-10">
      </template>
      <template v-slot:nextButton>
        <img src="~/assets/img/arrowOrange.svg" alt="arrowOrange" class="rotate-180 py-10">
      </template>
    </agile>    <h2 class="font-title text-3xl text-center">Et devenez le roi de la station</h2>
    <img src="~/assets/img/bike.png" alt="vélo" >
    <h2 class="font-title text-3xl text-center pt-10">Alors prêt à rider ?</h2>
    <div class="flex justify-center my-10">
<!--      <Button title="Télécharger l'application"/>-->
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
