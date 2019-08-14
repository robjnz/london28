
<template>
<section main>
  <b-container>

  <h1 class="asian">Free Tv Series to watch online </h1>

  <br><br>
  <b-card-group deck
  class="mb-3 ">
  <Handmaid /><!--The Handmaid's Tale-->
  <Blank />
  <Blank />
  </b-card-group>



      </b-container>
      </section>

</template>

<script>
import Handmaid from '@/components/series/Handmaid/Handmaid'
import Blank from '@/components/Films/Blank'







export default {
  head () {
    return {
      titleTemplate: '%s Free-Tv Series',
      meta         : [
        { hid: 'description', name: 'description', content: 'Free Tv series to watch online The Handmaids Tale' }
      ]
    }
  },
  components: {
    Blank,
    Handmaid,
    

      }
}
</script>
