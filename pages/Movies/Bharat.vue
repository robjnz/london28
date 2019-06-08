<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Bharat 12A ">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/Ea_GKoe81GY"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
          An 8-year-old boy makes a vow to his father that he will keep his family together no matter what, a promise that he works to keep over the next 60 years of his life.    </p>
    <Cineworld />
    <Odeon />
    <Picturehouses />
    <Showcase />
    <Vue />




  <h4 class="title-color"></h4>
  <b-button-group>
    <BharatR />
    <Nineteen />
  </b-button-group>

</b-card>
</b-container>
      </section>
</template>

<style>


</style>

<script>




import BharatR from '@/components/Films/Bharat/BharatR'
import Nineteen from '@/components/Films/Year/Nineteen'
import Cineworld from '@/components/Films/Bharat/Cineworld'
import Odeon from '@/components/Films/Bharat/Odeon'
import Picturehouses from '@/components/Films/Bharat/Picturehouses'
import Showcase from '@/components/Films/Bharat/Showcase'
import Vue from '@/components/Films/Bharat/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Bharat',
      meta         : [
        { hid: 'description', name: 'description', content: 'An 8-year-old boy makes a vow to his father that he will keep his family together no matter what, a promise that he works to keep over the next 60 years of his life.'}
      ]
    }
  },
  components: {
    BharatR,
    Nineteen,
    Cineworld,
    Odeon,
    Picturehouses,
    Showcase,
    Vue,
      }
}
</script>



