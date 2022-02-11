<template>
  <div>
    <div class="d-none d-md-block">
      <OurBrandMulti></OurBrandMulti>
    </div>
    <div class="d-md-none">
      <OurBrandSingle></OurBrandSingle>
    </div>
  </div>
</template>

<script>
import OurBrandMulti from '@/components/layouts/our-brand-multi'
import OurBrandSingle from '@/components/layouts/our-brand-single'

export default {
  name: 'OurBrand',
  components: {
    OurBrandMulti,
    OurBrandSingle,
  },
}
</script>

<style></style>
