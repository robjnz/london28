<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "X men Dark Phoenix 12A ">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/whoVmwVKYJE"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
        Jean Grey, as she evolves into the iconic dark phoenix. During a life-threatening rescue mission in space, Jean is hit by a cosmic force that transforms her into one of the most powerful mutants of all. Wrestling with this increasingly unstable power as well as her own personal demons, Jean spirals out of control, tearing the Xmen family apart and threatening to destroy the very fabric of our planet.    </p>
    <Cineworld />
    <Odeon />
    <Picturehouses />
    <Showcase />
    <Vue />




  <h4 class="title-color"></h4>
  <b-button-group>
    <XmenR />
    <Nineteen />
  </b-button-group>

</b-card>
</b-container>
      </section>
</template>

<style>


</style>

<script>


import XmenR from '@/components/Films/Xmen/XmenR'
import Nineteen from '@/components/Films/Year/Nineteen'
import Cineworld from '@/components/Films/Xmen/Cineworld'
import Odeon from '@/components/Films/Xmen/Odeon'
import Picturehouses from '@/components/Films/Xmen/Picturehouses'
import Showcase from '@/components/Films/Xmen/Showcase'
import Vue from '@/components/Films/Xmen/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s X men',
      meta         : [
        { hid: 'description', name: 'description', content: 'Jean Grey, as she evolves into the iconic dark phoenix. During a life-threatening rescue mission in space, Jean is hit by a cosmic force that transforms her into one of the most powerful mutants of all. Wrestling with this increasingly unstable power as well as her own personal demons, Jean spirals out of control, tearing the Xmen family apart and threatening to destroy the very fabric of our planet.'}
      ]
    }
  },
  components: {
    XmenR,
    Nineteen,
    Cineworld,
    Odeon,
    Picturehouses,
    Showcase,
    Vue,
      }
}
</script>



