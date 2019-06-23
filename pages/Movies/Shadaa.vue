<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Shadaa PG">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/ti94DXKnmkE"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
      Amidst pressures from his parents to hurry up and wed, a young man seeks his perfect match. After many failed attempts with matchmakers, his parents are delighted when their son finally meets the woman of his dreams, but things do not go as planned
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
import Cineworld from '@/components/Films/Shadaa/Cineworld'
import Odeon from '@/components/Films/Shadaa/Odeon'
import Picturehouses from '@/components/Films/Shadaa/Picturehouses'
import Showcase from '@/components/Films/Shadaa/Showcase'
import Vue from '@/components/Films/Shadaa/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Shadaa',
      meta         : [
        { hid: 'description', name: 'description', content: 'Amidst pressures from his parents to hurry up and wed, a young man seeks his perfect match. After many failed attempts with matchmakers, his parents are delighted when their son finally meets the woman of his dreams, but things do not go as planned'}
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



