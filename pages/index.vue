<template>
  <div>
    <Navbar/>
    <section class="hero is-link is-fullheight-with-navbar">
      <div class="hero-body">
        <div class="container">
          <div class="columns">
            <div class="column">
              <figure class="image is-128x128">
                <img src="https://bulma.io/images/placeholders/128x128.png">
              </figure>
              <div class="columns">
                <div class="column">
                  Hello
                </div>
                <div class="column">
                  Hello
                </div>
                <div class="column">
                  Hello
                </div>
              </div>
            </div>
            <div class="column">
              <button class="button secondary is-medium has-text-white is-fullwidth is-italic">Change Category</button>
              <button class="button secondary is-medium has-text-white is-fullwidth is-italic">Change Category</button>
              <button class="button secondary is-medium has-text-white is-fullwidth is-italic">Change Category</button>
              <button class="button secondary is-medium has-text-white is-fullwidth is-italic">Change Category</button>
            </div>
          </div>
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
    Navbar,
    Footer
  },
};
</script>