<template>
<b-card bg-variant="dark" text-variant="white" title= "Homeland">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/KyFmS3wRPCQ"
          allowfullscreen
  ></b-embed>
    <p class="title-color">
When Marine Sgt. Nicholas Brody returns home following eight years in captivity, CIA agent Carrie Mathison thinks he has turned and is connected to a terror plot to be carried out on American soil, so she engages him in a dangerous game of cat and mouse. 
</p>
<br><br><br><br><br><br><br>

<b-button block href="http://bit.ly/2KBUsdC" target="_blank" variant="info">Series 1 &rArr;</b-button>
<b-button block href="http://bit.ly/2z39Sko" target="_blank" variant="info">Series 2 &rArr;</b-button>
<b-button block href="http://bit.ly/2N5RijZ" target="_blank" variant="info">Series 3 &rArr;</b-button>
<b-button block href="http://bit.ly/2P0py2I" target="_blank" variant="info">Series 4 &rArr;</b-button>
<b-button block href="http://bit.ly/307vbgA" target="_blank" variant="info">Series 5 &rArr;</b-button>
<b-button block href="http://bit.ly/2Z5KzZQ" target="_blank" variant="info">Series 6 &rArr;</b-button>
<b-button block href="http://bit.ly/2OY9gHR" target="_blank" variant="info">Series 7 &rArr;</b-button>
<br><br>
<div>
  <b-button v-b-toggle.collapse-1 variant="primary">Toggle Collapse</b-button>
  <b-collapse id="collapse-1" class="mt-2">
    <b-card>
      <p class="asian">Collapse contents Here</p>
      <b-button v-b-toggle.collapse-1-inner size="sm">Toggle Inner Collapse</b-button>
      <b-collapse id="collapse-1-inner" class="mt-2">
        <b-card>Hello!</b-card>
      </b-collapse>
    </b-card>
  </b-collapse>
</div>
</b-card>

</template>

<style>


</style>

<script>







export default {
  components: {


      }
}
</script>



