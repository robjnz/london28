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
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Flondoneastlife-104681190948236%2F&tabs=timeline&width=320&height=600&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId" width = "360" height = "600" style = "border:none;overflow:hidden" scrolling = "no" frameborder = "0" allowTransparency = "true" allow = "encrypted-media"
          allowfullscreen
  ></b-embed>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
<!-- LightWidget WIDGET --><script src="https://cdn.lightwidget.com/widgets/lightwidget.js"></script><iframe src="//lightwidget.com/widgets/5a1774d4f53f53dc91ef8d91c85e019c.html" scrolling="yes" allowtransparency="true" class="lightwidget-widget" style="width:100%;border:0;overflow:hidden;"></iframe>
</b-card>

</b-card-group>
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.google.com/maps/d/embed?mid=1F9WADbgsmZ44JzTDdiOnHzyfux3uOFxI" width = "640" height = "480"
          allowfullscreen
  ></b-embed>


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
