<template>
<section show class="showcase">
    <b-container>

    <h1>What on in East London November 2019</h1>
    <br>

   <b-row class="text-center">
    <b-col><Barking /> </b-col>
    <b-col ><Greenwich /></b-col>
    <b-col><Orient /></b-col>
  </b-row>


    </b-container>
  </section>
</template>
<style scoped>
.showcase{
  background             : url(http://res.cloudinary.com/dzhbfdfa5/image/upload/v1515831480/tower_vow6im.jpg) no-repeat center center fixed;
  background-size        : cover;
  -webkit-background-size: cover;
  -moz-background-size   : cover;
  -o-background-size     : cover;
  height                 : 570px;
  margin-top             : -75px;

}

</style>

<script>

import Barking from '@/components/Theatres/Barking'
import Greenwich from '@/components/Theatres/Greenwich'
import Hackney from '@/components/Theatres/Hackney'
import Orient from '@/components/Football/Orient'


export default {

  components: {

Barking,
Greenwich,
Hackney,
Orient,

}
}
</script>
