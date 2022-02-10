<template>
<div >
  <div class="d-none d-md-block">
    <carouselView :value="value_md"></carouselView>
  </div>
  <div class="d-md-none">
    <carouselView :value="value_sm"></carouselView>
  </div>
</div>
</template>

<script>
import carouselView from "@/components/layouts/carousel-view";

export default {
  name: "CarouselItem",
  components: {
    carouselView,
  },
  data(){
    return {
      value_md: "550px",
      value_sm:" 250px",
    }
  },
  
}
</script>

<style scoped>

</style>