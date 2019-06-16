<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Dastaan-E-Miri Piri 12A">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/Gqo6_GP4vZQ"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
    Dastaan-E-Miri Piri unfolds the chapters of the Sikh history and conveys the history and teachings of Guru Hargobind Sahib Ji to the people through animation.    </p>
    <Cineworld />
    <Odeon />
    <Picturehouses />
    <Showcase />
    <Vue />




  <h4 class="title-color"></h4>
  <b-button-group>
    <Nineteen />
  </b-button-group>

</b-card>
</b-container>
      </section>
</template>

<style>


</style>

<script>




import Nineteen from '@/components/Films/Year/Nineteen'
import Cineworld from '@/components/Films/Dastaan/Cineworld'
import Odeon from '@/components/Films/Dastaan/Odeon'
import Picturehouses from '@/components/Films/Dastaan/Picturehouses'
import Showcase from '@/components/Films/Dastaan/Showcase'
import Vue from '@/components/Films/Dastaan/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Dastaan',
      meta         : [
        { hid: 'description', name: 'description', content: 'Dastaan-E-Miri Piri unfolds the chapters of the Sikh history and conveys the history and teachings of Guru Hargobind Sahib Ji to the people through animation.'}
      ]
    }
  },
  components: {
    Nineteen,
    Cineworld,
    Odeon,
    Picturehouses,
    Showcase,
    Vue,
      }
}
</script>



