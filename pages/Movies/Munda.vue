<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Munda Faridkotia PG">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/fJhqiYn2A40"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
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
import Cineworld from '@/components/Films/Munda/Cineworld'
import Odeon from '@/components/Films/Munda/Odeon'
import Picturehouses from '@/components/Films/Munda/Picturehouses'
import Showcase from '@/components/Films/Munda/Showcase'
import Vue from '@/components/Films/Munda/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Munda',
      meta         : [
        { hid: 'description', name: 'description', content: 'Munda Faridkotia.'}
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



