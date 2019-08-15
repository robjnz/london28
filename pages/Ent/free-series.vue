
<template>
<section main>
  <b-container>

  <h1 class="asian">Tv Series free to watch online </h1>

  <br><br>
  <b-card-group deck
  class="mb-3 ">
  <Grimm /><!--Grimm-->
  <Homeland /><!--Homeland -->
  <Handmaid /><!--The Handmaid's Tale-->
  
  
 
  </b-card-group>



      </b-container>
      </section>

</template>

<script>
import Grimm from '@/components/series/Grimm/Grimm'
import Handmaid from '@/components/series/Handmaid/Handmaid'
import Homeland from '@/components/series/Homeland'
import Blank from '@/components/Films/Blank'







export default {
  head () {
    return {
      titleTemplate: '%s Free-Tv Series',
      meta         : [
        { hid: 'description', name: 'description', content: 'Free Tv series to watch online Grimm, Homeland, The Handmaids Tale' }
      ]
    }
  },
  components: {
    Blank,
    Grimm,
    Handmaid,
    Homeland,
      }
}
</script>
