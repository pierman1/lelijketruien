<template>
  <section class="container">
    <div>
      <Header/>
      <h1 class="title">
        lelijketruien
      </h1>
      <h2 class="subtitle">
        Nuxt.js project
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a>
      </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import Header from '~/components/header'

export default {
  components: {
    Header
  }
}
</script>

<style>
.container {
  min-height: 100vh;
}
</style>
