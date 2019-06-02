<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Godzilla king Of The Monsters 12A ">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/GbXQHYfUhtg"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
    Members of the crypto-zoological agency Monarch face off against a battery of god-sized monsters, including the mighty Godzilla, who collides with Mothra, Rodan, and his ultimate nemesis, the three-headed King Ghidorah. When these ancient super-species-thought to be mere myths-rise again, they all vie for supremacy, leaving humanity's very existence hanging in the balance.    </p>
    <Cineworld />
    <Odeon />
    <Picturehouses />
    <Showcase />
    <Vue />




  <h4 class="title-color"></h4>
  <b-button-group>
    <GodzillaR />
    <Nineteen />
  </b-button-group>

</b-card>
</b-container>
      </section>
</template>

<style>


</style>

<script>




import GodzillaR from '@/components/Films/Godzilla/GodzillaR'
import GodzillaF from '@/components/Films/Godzilla/GodzillaF'
import Nineteen from '@/components/Films/Year/Nineteen'
import Cineworld from '@/components/Films/Godzilla/Cineworld'
import Odeon from '@/components/Films/Godzilla/Odeon'
import Picturehouses from '@/components/Films/Godzilla/Picturehouses'
import Showcase from '@/components/Films/Godzilla/Showcase'
import Vue from '@/components/Films/Godzilla/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Godzilla',
      meta         : [
        { hid: 'description', name: 'description', content: 'Members of the crypto-zoological agency Monarch face off against a battery of god-sized monsters, including the mighty Godzilla, who collides with Mothra, Rodan, and his ultimate nemesis, the three-headed King Ghidorah. When these ancient super-species-thought to be mere myths-rise again, they all vie for supremacy, leaving humanitys very existence hanging in the balance.'}
      ]
    }
  },
  components: {
    GodzillaR,
    GodzillaF,
    Nineteen,
    Cineworld,
    Odeon,
    Picturehouses,
    Showcase,
    Vue,
      }
}
</script>



