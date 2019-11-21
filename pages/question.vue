<template>
  <div>
    <section class="hero is-link is-fullheight-with-navbar">
      <div class="hero-body">
        <div class="container">
          <p class="title">
            Fullheight hero with navbar
          </p>
        </div>
      </div>
    </section>
    <section class="section">
      <button class="button is-primary is-medium is-fullwidth is-italic has-text-weight-bold has-text-left question">Q:What is the best football club in the world ?</button>
      <div class="columns">
        <div class="column">
          <button class="button is-primary is-medium is-fullwidth is-italic">Entertainment</button>
          <button class="button is-primary is-medium is-fullwidth is-italic">Sports</button>
          <p class="has-text-centered is-italic has-text-primary is-size-4 has-text-weight-semibold">SKIP</p>
        </div>
        <div class="column">
          <button class="button is-primary is-medium is-fullwidth is-italic">Education</button>
          <button class="button is-primary is-medium is-fullwidth is-italic">World</button>
          <button class="button secondary is-medium has-text-white is-fullwidth is-italic">Change Category</button>
        </div>
      </div>
    </section>
    <Footer/>
  </div>
</template>

<script>
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Footer
  }
}
</script>

<style>

</style>