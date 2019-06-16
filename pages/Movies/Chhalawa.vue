<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Chhalawa 12A">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/bZdzMJH5110"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
      The film Chhalawa revolves around love, relationships and family
    </p>
    <Cineworld />
    <Odeon />
    <Picturehouses />
    <Showcase />
    <Vue />




  <h4 class="title-color"></h4>
  <b-button-group>
    <ChhalawaR />
    <Nineteen />
  </b-button-group>

</b-card>
</b-container>
      </section>
</template>

<style>


</style>

<script>




import ChhalawaR from '@/components/Films/Chhalawa/ChhalawaR'
import Nineteen from '@/components/Films/Year/Nineteen'
import Cineworld from '@/components/Films/Chhalawa/Cineworld'
import Odeon from '@/components/Films/Chhalawa/Odeon'
import Picturehouses from '@/components/Films/Chhalawa/Picturehouses'
import Showcase from '@/components/Films/Chhalawa/Showcase'
import Vue from '@/components/Films/Chhalawa/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Chhalawa',
      meta         : [
        { hid: 'description', name: 'description', content: 'The film Chhalawa revolves around love, relationships and family.'}
      ]
    }
  },
  components: {
    ChhalawaR,
    Nineteen,
    Cineworld,
    Odeon,
    Picturehouses,
    Showcase,
    Vue,
      }
}
</script>



