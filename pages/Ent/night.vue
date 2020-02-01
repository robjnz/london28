<template>
<section main>
  <b-container>
    <h1 class="title-color">What on this month @ East London Night clubs</h1>
    <h2>February 2020</h2>
    <br>

    <b-card-group deck
    class="mb-3">
<ATIK />

<b-card bg-variant="dark" text-variant="white" title= "Bar300 Walthamstow">
  <p class="title-color">
  <a href="https://kutt.it/bar300" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1551026332/bar300_j26uzg.jpg" fluid-grow alt="Bar300 Walthamstow" /></a>
    </p>
    <b-button href="https://kutt.it/bar300" target="_blank" variant="info">open</b-button>
<br>300 Hoe Street <br>Walthamstow London 17 9QD
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Faces Nightclub Ilford ">
  <p class="title-color">
  <a href="https://kutt.it/faces-ilford" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1549703857/faces_zpm8ou.jpg" fluid-grow alt="Faces nightclub Ilford" /></a>
    </p>
    <b-button href="https://kutt.it/faces-ilford" target="_blank" variant="info">open</b-button>
  <br>458-462 Cranbrook Road <br>Gants Hill Ilford Essex IG2 6LE
</b-card>
    </b-card-group>

  <b-card-group deck
    class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Jhankaar Stratford">
  <p class="title-color">
  <a href="https://kutt.it/jhankaa-club" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1551026881/Jhankaar_Club_q0bnqr.jpg" fluid-grow alt="Jhankaar Stratford" /></a>
    </p>
    <b-button href="https://kutt.it/jhankaa-club" target="_blank" variant="info">open</b-button>
<br>Jhankaar Club 27 Broadway<br> Stratford London E15 4BQ
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "kings Bull Barking">
  <p class="title-color">
  <a href="https://kutt.it/kings-club" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1550941361/Kings-Bull_xgogbn.jpg" fluid-grow alt="kings bull Barking" /></a>
    </p>
    <b-button href="https://kutt.it/kings-club" target="_blank" variant="info">open</b-button>
<br>
2 North strret Barking IG11 8ET<br>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "The Hoxton Pony">
  <p class="title-color">
  <a href="" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1551112431/hoxtonpony_zzqf5u.jpg" fluid-grow alt="The Hoxton Pony" /></a>
    </p>
    <!--
    <b-button href="https://kutt.it/hoxtonpony" target="_blank" variant="info">open</b-button>
    -->
<br>104-108 Curtain Road London EC2A 3AH
</b-card>

</b-card-group>

  <b-card-group deck
    class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "XOYO Shoreditch">
  <p class="title-color">
  <a href="https://kutt.it/xoyo" target="_blank"><b-img src="https://res.cloudinary.com/dzhbfdfa5/image/upload/c_scale,h_180,w_300/v1551027628/xoyo_uel6gt.jpg" fluid-grow alt="XOYO Shoreditch" /></a>
    </p>
    <b-button href="https://kutt.it/xoyo" target="_blank" variant="info">open</b-button>
<br>32-37 Cowper Steet<br>London EC2A 4AW
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">
    </p>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">
    </p>
</b-card>
    </b-card-group>




      </b-container>
      </section>

</template>

<script>
import ATIK from '@/components/Nightclubs/ATIK'

export default {
  head () {
    return {
      titleTemplate: '%s Night clubs',
      meta         : [
        { hid: 'description', name: 'description', content: 'Whats on @ the east London night clubs this month, February 2020.' }
      ]
    }
  },
  components: {
ATIK,
}
}
</script>
