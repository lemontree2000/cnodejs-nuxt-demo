<template>
  <div>
    <Header />
    <nuxt />
    <Footer />
  </div>
</template>
<script>
import Footer from '~/components/layouts/Footer'
import Header from '~/components/layouts/Header'

export default {
  components: {
    Footer,
    Header
  },
  data() {
    return {
      isFor: true
    }
  },
  methods: {
    getName() {
      console.log(2)
    }
  }
}
</script>
