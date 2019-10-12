const newLocal="https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v4.0"
<template>
<section main>
  <b-container>
    <h1 class="title-color">This months events in East London</h1>
    <h2>October 2019</h2>
    <br>
    <b-card-group deck
class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "">
<a class="twitter-timeline" data-width="320" data-height="600" data-theme="dark" href="https://twitter.com/londoneast3?ref_src=twsrc%5Etfw">Tweets by londoneast3</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">

</b-card>
<b-card bg-variant="dark" text-variant="white" title= "">

</b-card>
    </b-card-group>

 <b-card-group deck
class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "">
<!-- Place <div> tag where you want the feed to appear -->
<div id="curator-feed-default-layout"><a href="https://curator.io" target="_blank" class="crt-logo crt-tag">Powered by Curator.io</a></div>
<!-- The Javascript can be moved to the end of the html page before the </body> tag -->
<script type="text/javascript">
/* curator-feed-default-layout */
(function(){
var i,     e, d = document, s = "script";i = d.createElement("script");i.async = 1;
    i.src = "https://cdn.curator.io/published/df50401c-f6ed-4798-bef7-f3311a5124d0.js";
    e     = d.getElementsByTagName(s)[0];e.parentNode.insertBefore(i, e);
})();
</script>
</b-card>
 </b-card-group>


  <b-card-group deck
class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "">
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.google.com/maps/d/embed?mid=1F9WADbgsmZ44JzTDdiOnHzyfux3uOFxI" width = "640" height = "480"
          allowfullscreen
  ></b-embed>
</b-card>
 </b-card-group>

</b-container>
      </section>

</template>

<script>
export default {
  head () {
    return {
      titleTemplate: '%s todays events',
      meta         : [
        { hid: 'description', name: 'description', content: 'This months events in east London October 2019' }
      ]
    }
  }
}
</script>
