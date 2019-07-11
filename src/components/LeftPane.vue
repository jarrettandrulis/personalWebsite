<template>
  <div>
    <section class="section split left-bg"/>
      <section class="section split left">
        <section class="section centered">
          <h1 class="title is-1 j-title text-outline">Jarrett Andrulis</h1>
          <h2 class="subtitle is-4 j-subtitle text-outline">Just a programmer from Chicago</h2>
        </section>
    </section>
  </div>
</template>

<script>

export default {
  name: 'LeftPane',
  components: {
  },
  data () {
    return {
    }
  },
  methods:
  {
  }
}
</script>
<style>
  .left {
    left: 0;
  }
  .left-bg {
    background-image: url('../assets/chicago.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    -webkit-filter: blur(3px);
    -moz-filter: blur(3px);
    -o-filter: blur(3px);
    -ms-filter: blur(3px);
    filter: blur(3px);
  }
  .centered {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    text-align: center;
  }
  .j-title {
    font-family: "Montserrat";
    color: white;
  }
  .j-subtitle {
    font-family: "Lora";
    color: white;
  }
</style>
