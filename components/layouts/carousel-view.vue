<template>
    <el-carousel :interval="4000" type="card" arrow="always" :height="value" >
      <el-carousel-item >
        <img src="~/assets/img/pexels-5.jpg" class="item__image" alt=""/>
      </el-carousel-item>
      <el-carousel-item >
        <img src="~/assets/img/pexels-4.jpg" class="item__image" alt=""/>
      </el-carousel-item>
      <el-carousel-item >
        <img src="~/assets/img/pexels-3.jpg" class="item__image" alt=""/>
      </el-carousel-item>
      <el-carousel-item >
        <img src="~/assets/img/pexels-2.jpg" class="item__image" alt=""/>
      </el-carousel-item>
      <el-carousel-item >
        <img src="~/assets/img/pexels-1.jpg"  class="item__image" alt=""/>
      </el-carousel-item>
    </el-carousel>
</template>

<script>
export default {
  name: "carousel-view",
  props:["value"],
}
</script>

<style scoped>
.item__image {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>