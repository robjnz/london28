<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Rocketman 15">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/S3vO8E2e6G0"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
      An epic musical fantasy about the uncensored human story of Sir Elton John’s breakthrough years.
    </p>
    <Cineworld />
    <Odeon />
    <Picturehouses />
    <Showcase />
    <Vue />




  <h4 class="title-color"></h4>
  <b-button-group>
    <RocketmanR />
    <RocketmanF />
    <Nineteen />
  </b-button-group>

</b-card>
</b-container>
      </section>
</template>

<style>


</style>

<script>




import RocketmanR from '@/components/Films/Rocketman/RocketmanR'
import RocketmanF from '@/components/Films/Rocketman/RocketmanF'
import Nineteen from '@/components/Films/Year/Nineteen'
import Cineworld from '@/components/Films/Rocketman/Cineworld'
import Odeon from '@/components/Films/Rocketman/Odeon'
import Picturehouses from '@/components/Films/Rocketman/Picturehouses'
import Showcase from '@/components/Films/Rocketman/Showcase'
import Vue from '@/components/Films/Rocketman/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Rocketman',
      meta         : [
        { hid: 'description', name: 'description', content: 'An epic musical fantasy about the uncensored human story of Sir Elton John’s breakthrough years.'}
      ]
    }
  },
  components: {
    RocketmanR,
    RocketmanF,
    Nineteen,
    Cineworld,
    Odeon,
    Picturehouses,
    Showcase,
    Vue,
      }
}
</script>



