<template>
  <div>
    <div id="booknow">
      <b-button>Call or Book Online Now</b-button>
    </div>
    <article class="media" id="introtext">
  <figure class="media-left">
    <p class="image is-128x128">
      <img id="headshot" class="effect1" src="../assets/kim_face.jpg">
    </p>
  </figure>
  <div class="media-content">
    <div class="content">
      <p>
        <strong>Kimberly Slaven</strong> <small>@kimslaven</small>
        <br>
        My name is Kim and I offer a full range of services at Bronze Beauty Full Service Salon in LaPine, Oregon.
      </p>
    </div>
  </div>
</article>

    <p id="introtext">
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style>
#booknow {
  margin-top: 40px;
}

.effect1{
    -webkit-box-shadow: 0 10px 6px -6px #777;
       -moz-box-shadow: 0 10px 6px -6px #777;
            box-shadow: 0 10px 6px -6px #777;
}

#headshot {
  border-radius: 3px;
}

#introtext {
  margin-top: 30px;
  padding: 30px;
  text-align: left;
}
</style>