<template>
  <div class="home">
    <section class="hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">{{ heading }}</h1>
          <div class="is-two-thirfs column is-paddingless">
            <h2 class="subtitle is-4"> {{ subheading }}</h2>
          </div>
          <a class="button is-large is-primary" id="learn">Learn more</a>

        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'home',
  data() {
    return {
      heading: 'Soaromg to new heights',
      subheading: 'Lorem ipsum dolor sit amet, consecterum adipsit elit, sed do eisumod tempor incididunt ut labore et dolore magna aliqua'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
@import '../mq'


</style>
