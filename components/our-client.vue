<template>
  <div>
    <div class="d-none d-md-block">
      <OurClientMulti></OurClientMulti>
    </div>
    <div class="d-md-none">
      <OurClientSingle></OurClientSingle>
    </div>
  </div>
</template>

<script>
import OurClientMulti from '@/components/layouts/our-client-multi'
import OurClientSingle from '@/components/layouts/our-client-single'

export default {
  name: 'OurClient',
  components: {
    OurClientMulti,
    OurClientSingle,
  },
}
</script>

<style></style>
