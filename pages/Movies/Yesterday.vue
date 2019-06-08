<template>
<section main>
  <b-container>
<b-card bg-variant="dark" text-variant="white" title= "Yesterday 12A">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/6uqvgPm8U4c"
          allowfullscreen
  ></b-embed>

    <p class="title-color">
      Jack Malik is a struggling singer-songwriter in an English seaside town whose dreams of fame are rapidly fading, despite the fierce devotion and support of his childhood best friend, Ellie. After a freak bus accident during a mysterious global blackout, Jack wakes up to discover that The Beatles have never existed. Performing songs by the greatest band in history to a world that has never heard them, Jack becomes on overnight sensation with a little help from his agent.    </p>
    <Cineworld />
    <Odeon />
    <Picturehouses />
    <Showcase />
    <Vue />




  <h4 class="title-color"></h4>
  <b-button-group>
    <YesterdayR />
    <Nineteen />
  </b-button-group>

</b-card>
</b-container>
      </section>
</template>

<style>


</style>

<script>




import YesterdayR from '@/components/Films/Yesterday/YesterdayR'
import Nineteen from '@/components/Films/Year/Nineteen'
import Cineworld from '@/components/Films/Yesterday/Cineworld'
import Odeon from '@/components/Films/Yesterday/Odeon'
import Picturehouses from '@/components/Films/Yesterday/Picturehouses'
import Showcase from '@/components/Films/Yesterday/Showcase'
import Vue from '@/components/Films/Yesterday/Vue'





export default {
    head () {
    return {
      titleTemplate: '%s Yesterday',
      meta         : [
        { hid: 'description', name: 'description', content: 'Jack Malik is a struggling singer-songwriter in an English seaside town whose dreams of fame are rapidly fading, despite the fierce devotion and support of his childhood best friend, Ellie. After a freak bus accident during a mysterious global blackout, Jack wakes up to discover that The Beatles have never existed. Performing songs by the greatest band in history to a world that has never heard them, Jack becomes on overnight sensation with a little help from his agent.'}
      ]
    }
  },
  components: {
    YesterdayR,
    Nineteen,
    Cineworld,
    Odeon,
    Picturehouses,
    Showcase,
    Vue,
      }
}
</script>



