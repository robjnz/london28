<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Kabir Singh 15">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/RiANSSgCuJk"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
      A house surgeon goes into a self-destructive spiral after his girlfriend is forced to marry another man.
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
import Cineworld from '@/components/Films/Asian/Kabir/Cineworld'
import Odeon from '@/components/Films/Asian/Kabir/Odeon'
import Picturehouses from '@/components/Films/Asian/Kabir/Picturehouses'
import Showcase from '@/components/Films/Asian/Kabir/Showcase'
import Vue from '@/components/Films/Asian/Kabir/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Kabir',
      meta         : [
        { hid: 'description', name: 'description', content: 'A house surgeon goes into a self-destructive spiral after his girlfriend is forced to marry another man.'}
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



