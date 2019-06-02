<template>
<section main>
  <b-container>
    <h1 class="title-color">What on this month @ East London Theatres</h1>
    <h2>June 2019</h2>
    <br>
    <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Sherlock Holmes The Sign of Four">
  <p class="title-color">
  <b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/7eiwlCWhRFQ"
          allowfullscreen
  ></b-embed>
    Broadway Theatre Barking<br>
    Thurs 6 - Fri 7 June 2019


    </p>

    <b-button href="https://kutt.it/barkingt" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "A Womb of One's Own">
  <p class="title-color">
    Greenwich Theatre<br>
    Wed 29 May 2019 @ 7.30pm
    </p>
    <b-button href="https://kutt.it/greenwichT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "In The Night Garden">
  <p class="title-color">
      <b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/-wv-MkkErQ0"
          allowfullscreen
  ></b-embed>
    Hackney Empire<br>
    Sat 01 - Sun 02 Jun 2019

    </p>
    <b-button href="https://kutt.it/hackneyT" target="_blank" variant="info">open</b-button>

</b-card>
    </b-card-group>

        <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Block Universe">
  <p class="title-color">
    Hoxton Hall<br>
    Thurs 30 - Fri 31 May @ 7.30pm
    </p>
    <b-button href="https://kutt.it/hoxtonT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Copacabanna">

  <p class="title-color">
    Kenneth More Theatre Ilford<br>
    Thu 6 - Sat 8 June 2019

</p>
    <b-button href="https://kutt.it/ilfordT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "The Jeff Short Big Swing Band & Singers">


  <p class="title-color">

    Queen's Theatre Hornchurch<br>
    Wed 29 May 2019 @ 2.30pm

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
          src    = "https://www.youtube.com/embed/rdIhxQSm6Rg"
          allowfullscreen
  ></b-embed>

    Theatre Royal Stratford East<br>
    Fri 17 - Sat 15 June 2019

    </p>
    <b-button href="https://kutt.it/stratfordeastT" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Tame Impala">
  <p class="title-color">
    The O2 arena<br>
    Sat 8 June 2019 @ 6.30 pm

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
