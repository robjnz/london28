<template>
<section main>
  <b-container>
    <h1 class="title-color">What on this month @ East London Theatres</h1>
    <h2>August 2019</h2>
    <br>
    <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Shadow of the Past">
  <p class="title-color">

    Broadway Theatre Barking<br>
    Fri 6 Sep 2019 @ 8pm
    </p>
<p class="asian">
    Shadow of the Past is a movie full of comedy, romance and suspense.  A beautiful girl called Rachel who has a terrible past and has been abused by her uncle and her auntie has turned a blind eye.  She fell in love with a man called Mike who seemed to love her but as time goes on she realised the love was false.
</p>

<p class="labour">
  £20 per person
  </p>

    <b-button href="https://kutt.it/barkingt" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Shane Mauss & Adam Strauss">
  <p class="title-color">
    Greenwich Theatre<br>
    Thurs 15 Aug 2019 @ 7.30pm
    </p>
<p class="asian">
    Shane Mauss and Adam Strauss a fantastic night of Psychedelic Comedy.
</p>
<br><br><br><br><br><br>
<p class="labour">
  £41 per person
  </p>

    <b-button href="https://kutt.it/greenwichT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Avenue Q">
  <p class="title-color">

    Hackney Empire<br>
    Mon 19 - Sat 24 Aug - 7.30pm

    </p>
    <b-button href="https://kutt.it/hackneyT" target="_blank" variant="info">open</b-button>

</b-card>
    </b-card-group>

        <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Chasing Rainbows">
  <p class="title-color">
    <b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/AG074obtosk"
          allowfullscreen
  ></b-embed>
    Hoxton Hall<br>
    Tue 25 June - Sat 20 July 2019
    </p>
    <b-button href="https://kutt.it/hoxtonT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Tina Turner Experience">

  <p class="title-color">
    <b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/mlQBlQ-Z94Q"
          allowfullscreen
  ></b-embed>
    Kenneth More Theatre Ilford<br>
    Sat 27 July @ 7.30pm

</p>
    <b-button href="https://kutt.it/ilfordT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "The Carpenters">


  <p class="title-color">
<b-embed type = "iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/8JM2BTCNnH0"
          allowfullscreen
  ></b-embed>
    Queen's Theatre Hornchurch<br>
    Mon 8 July 2019 @ 7.30pm

    </p>
    <b-button href="https://kutt.it/queensT" target="_blank" variant="info">open</b-button>

</b-card>

    </b-card-group>

    <b-card-group deck
      class="mb-3">
  <b-card bg-variant="dark" text-variant="white" title= "Noye's Fludde">
  <p class="title-color">
      <p class="title-color">

    Theatre Royal Stratford East<br>
    Mon 01 - Sat 13 July 2019

    </p>
    <b-button href="https://kutt.it/stratfordeastT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Kiss">
  <p class="title-color">
    The O2 arena<br>
    Thur 11 July 2019 @ 6.30pm

    </p>
    <b-button href="https://kutt.it/Theo2T" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Beauty & The Beat Beauty">
  <p class="title-color">

    The Yard Hackney<br>
    Sat 29 June 2019 @ 10pm

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
        { hid: 'description', name: 'description', content: 'Whats on at the east London Theatres this month, August 2019, Hackney empire, Kenneth More Theatre Ilford, Theatre Royal Stratford East and more!' }
      ]
    }
  }
}
</script>
