<template>
  <div class="container-fluid">
    <TopNavBar></TopNavBar>
    <Nuxt />
    <Footer></Footer>
  </div>
</template>

<script>
import TopNavBar from '@/components/TopNavBar'
import Footer from '@/components/layouts/footer'

export default {
  name: 'DefaultVVue',
  components: {
    TopNavBar,
    Footer,
  },
}
</script>

<style scoped></style>
