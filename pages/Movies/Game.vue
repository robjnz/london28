<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Game Over 18">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/JUswBxwJvaQ"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
    As the news of a serial killer on the loose sends the city into a tailspin, a young woman suffering from PTSD starts sensing a strange presence around her. Is there a dreadful fate awaiting her?
    </p>
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
import Cineworld from '@/components/Films/Game/Cineworld'
import Odeon from '@/components/Films/Game/Odeon'
import Picturehouses from '@/components/Films/Game/Picturehouses'
import Showcase from '@/components/Films/Game/Showcase'
import Vue from '@/components/Films/Game/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Game',
      meta         : [
        { hid: 'description', name: 'description', content: 'As the news of a serial killer on the loose sends the city into a tailspin, a young woman suffering from PTSD starts sensing a strange presence around her. Is there a dreadful fate awaiting her?'}
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



