<template>
<section main>
  <b-container>
    <h1 class="title-color">What on this month @ East London Theatres</h1>
    <h2>June 2019</h2>
    <br>
    <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Future Faces - Bugsy Malone">
  <p class="title-color">

    Broadway Theatre Barking<br>
    Sun 16 June 2019 @ 7.30pm


    </p>

    <b-button href="https://kutt.it/barkingt" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Sirens">
  <p class="title-color">
    Greenwich Theatre<br>
    Thurs 20 - Sun 23 June 2019 @7.30pm
    </p>
    <b-button href="https://kutt.it/greenwichT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "An Evening with Sandi Toksvig">
  <p class="title-color">

    Hackney Empire<br>
    Thurs 27 June 2019 7.30pm

    </p>
    <b-button href="https://kutt.it/hackneyT" target="_blank" variant="info">open</b-button>

</b-card>
    </b-card-group>

        <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Chasing Rainbows">
  <p class="title-color">
    Hoxton Hall<br>
    Tue 25 June - Sat 20 July 2019
    </p>
    <b-button href="https://kutt.it/hoxtonT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Imagine">

  <p class="title-color">
    Kenneth More Theatre Ilford<br>
    Fri 21 - Sat 22 June 2019

</p>
    <b-button href="https://kutt.it/ilfordT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Charge">


  <p class="title-color">
    <b-embed type = "iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/sXYFAjzNtXs"
          allowfullscreen
  ></b-embed>

    Queen's Theatre Hornchurch<br>
    Tues 11 June 2019 @ 7.30pm

    </p>
    <b-button href="https://kutt.it/queensT" target="_blank" variant="info">open</b-button>

</b-card>

    </b-card-group>

    <b-card-group deck
      class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "King Hedley II">
  <p class="title-color">
      <p class="title-color">
    <b-embed type = "iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/XYM4rYtOVkI"
          allowfullscreen
  ></b-embed>

    Theatre Royal Stratford East<br>
    Fri 17 May - Sat 15 June 2019

    </p>
    <b-button href="https://kutt.it/stratfordeastT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Mamma Mia! The Party">
  <p class="title-color">
    The O2 arena<br>
    Summer 2019

    </p>
    <b-button href="https://kutt.it/Theo2T" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Armadillo">
  <p class="title-color">
<b-embed type = "iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/RPfTLX-mxGQ"
          allowfullscreen
  ></b-embed>

    The Yard Hackney<br>
    Thurs 30 May — Sat 22 June 2019

    </p>
    <b-button href="https://kutt.it/yardT" target="_blank" variant="info">open</b-button>

</b-card>


    </b-card-group>
    <!--
      <div>


      <b-card-group deck
      class="mb-3">
    <b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">

  </p>
  <b-button-group>
  <b-button href="http://bit.ly/2O857LG" target="_blank" variant="info">Broadway Theatre Barking</b-button>
  <b-button href="http://bit.ly/2CKtih3" target="_blank" variant="info">Greenwich Theatre</b-button>
  <b-button href="http://bit.ly/2JnhX7Z" target="_blank" variant="info">Hackney Empire</b-button>
  </b-button-group>
  <br>
  <br>
  <b-button-group>
  <b-button href="http://bit.ly/2EX7IsG" target="_blank" variant="info">Hoxton Hall</b-button>
  <b-button href="http://bit.ly/2D9UPtc" target="_blank" variant="info">Kenneth More Theatre Ilford</b-button>
  <b-button href="http://bit.ly/2Soh3MB" target="_blank" variant="info">Queen's Theatre Hornchurch</b-button>
  </b-button-group>
  <br>
  <br>
  <b-button-group>
  <b-button href="http://bit.ly/2JjU3Kr" target="_blank" variant="info">Theatre Royal Stratford East</b-button>
  <b-button href="http://bit.ly/2PpXswU" target="_blank" variant="info">The 02</b-button>
  <b-button href="http://bit.ly/2OYFsdx" target="_blank" variant="info">The Yard Hackney</b-button>
  </b-button-group>

  </b-card>
  </b-card-group>

</div>
-->
      </b-container>
      </section>

</template>

<script>
export default {
  head () {
    return {
      titleTemplate: '%s theatres',
      meta         : [
        { hid: 'description', name: 'description', content: 'Whats on at the east London Theatres this month, June 2019, Hackney empire, Kenneth More Theatre Ilford, Theatre Royal Stratford East and more!' }
      ]
    }
  }
}
</script>
