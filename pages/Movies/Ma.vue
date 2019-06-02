<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Ma 15 ">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/3NKDf71jy1I"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
      A lonely middle-aged woman befriends some teenagers and decides to let them party in the basement of her home. But there are some house rules. Ma's hospitality starts to curdle into obsession, what began as a teenage dream turns into a terrorizing nightmare.    </p>
    <Cineworld />
    <Odeon />
    <Picturehouses />
    <Showcase />
    <Vue />




  <h4 class="title-color"></h4>
  <b-button-group>
    <MaR />
    <Nineteen />
  </b-button-group>

</b-card>
</b-container>
      </section>
</template>

<style>


</style>

<script>




import MaR from '@/components/Films/Ma/MaR'
import MaF from '@/components/Films/Ma/MaF'
import Nineteen from '@/components/Films/Year/Nineteen'
import Cineworld from '@/components/Films/Ma/Cineworld'
import Odeon from '@/components/Films/Ma/Odeon'
import Picturehouses from '@/components/Films/Ma/Picturehouses'
import Showcase from '@/components/Films/Ma/Showcase'
import Vue from '@/components/Films/Ma/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Ma',
      meta         : [
        { hid: 'description', name: 'description', content: 'A lonely middle-aged woman befriends some teenagers and decides to let them party in the basement of her home. But there are some house rules. Ma hospitality starts to curdle into obsession, what began as a teenage dream turns into a terrorizing nightmare.'}
      ]
    }
  },
  components: {
    MaR,
    MaF,
    Nineteen,
    Cineworld,
    Odeon,
    Picturehouses,
    Showcase,
    Vue,
      }
}
</script>



