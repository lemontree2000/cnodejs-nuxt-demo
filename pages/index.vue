<template>
  <section class="container">
    <div>
      <logo />
      <h1 class="title">
        cnodejs-nuxt-demo
      </h1>
      <h2 class="subtitle">
        My solid Nuxt.js project
      </h2>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">DocumentationDocumentation</a>
        <a href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey">GitHub </a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>
