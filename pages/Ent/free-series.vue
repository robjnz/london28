
<template>
<section main>
  <b-container>

  <h1 class="asian">Tv Series free to watch online </h1>

  <br><br>
  <b-card-group deck
  class="mb-3 ">
  <Thrones /><!--Game of Thrones-->
  <Grimm /><!--Grimm-->
  <Homeland /><!--Homeland -->
  </b-card-group>

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
import Thrones from '@/components/series/Thrones'
import Grimm from '@/components/series/Grimm'
import Handmaid from '@/components/series/Handmaid'
import Homeland from '@/components/series/Homeland'
import Blank from '@/components/Films/Blank'







export default {
  head () {
    return {
      titleTemplate: '%s Free-Tv Series',
      meta         : [
        { hid: 'description', name: 'description', content: 'Free Tv series to watch online Game of Thrones, Grimm, Homeland, The Handmaids Tale' }
      ]
    }
  },
  components: {
    Blank,
    Grimm,
    Handmaid,
    Homeland,
    Thrones,
      }
}
</script>
