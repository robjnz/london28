<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Aladdin PG ">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/foyufD52aog"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
      Young Aladdin embarks on a magical adventure after finding a lamp that releases a wisecracking genie.
    </p>
    <Cineworld />
    <Odeon />
    <Picturehouses />
    <Showcase />
    <Vue />




  <h4 class="title-color"></h4>
  <b-button-group>
    <AladdinR />
    <AladdinF />
    <Nineteen />
  </b-button-group>

</b-card>
</b-container>
      </section>
</template>

<style>


</style>

<script>




import AladdinR from '@/components/Films/Aladdin/AladdinR'
import AladdinF from '@/components/Films/Aladdin/AladdinF'
import Nineteen from '@/components/Films/Year/Nineteen'
import Today from '@/components/Films/Aladdin/Today'
import Cineworld from '@/components/Films/Aladdin/Cineworld'
import Odeon from '@/components/Films/Aladdin/Odeon'
import Picturehouses from '@/components/Films/Aladdin/Picturehouses'
import Showcase from '@/components/Films/Aladdin/Showcase'
import Vue from '@/components/Films/Aladdin/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Aladdin',
      meta         : [
        { hid: 'description', name: 'description', content: 'Young Aladdin embarks on a magical adventure after finding a lamp that releases a wisecracking genie.'}
      ]
    }
  },
  components: {
    AladdinR,
    AladdinF,
    Nineteen,
    Today,
    Cineworld,
    Odeon,
    Picturehouses,
    Showcase,
    Vue,
      }
}
</script>



