<template>
  <div>
    <Navbar/>
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
      <div class="columns">
        <div class="column">
          <button class="button is-primary is-medium is-fullwidth is-italic">Entertainment</button>
          <button class="button is-primary is-medium is-fullwidth is-italic">Sports</button>
          <button class="button is-primary is-medium is-fullwidth is-italic">Animals</button>
        </div>
        <div class="column">
          <button class="button is-primary is-medium is-fullwidth is-italic">Education</button>
          <button class="button is-primary is-medium is-fullwidth is-italic">World</button>
          <button class="button is-primary is-medium is-fullwidth is-italic">Bible</button>
        </div>
        <div class="column">
          <button class="button is-primary is-medium is-fullwidth is-italic">Politics</button>
          <button class="button is-primary is-medium is-fullwidth is-italic">Countries</button>
          <button class="button secondary is-medium is-fullwidth is-italic">Play Now</button>
        </div>
        <div class="column">
          <img src="../assets/prize.png" alt="Prize draw">
        </div>
      </div>
    </section>
    <Footer/>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Footer,
    Navbar
  }
}
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

