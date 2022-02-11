<template>
  <div>
    <Carousel></Carousel>
    <div class="mt-5">
      <div class="row">
        <div class="col-md-8">
          <div class="row">
            <div class="col-md">
              <h4>
                Who <span class="text-danger font-weight-bold">We Are</span>
              </h4>
            </div>
          </div>
          <div class="row">
            <div class="col-md">
              <p class="text-justify">
                United Engineering has customized services which helps
                Bangladeshi readymade Garments Manufacturers to Comply with
                ACCORD & ALLIANCE. During this time FIRE SAFETY, ELECTRICAL
                SAFETY & Micro control have become specialists in planned
                preventative maintenance as well as Installations. We will
                continue working hard to build long time trusting relationship
                with our customers. We aim for the highest standards of business
                excellence by employing & supporting motivated, flexible and
                focused staff and maintaining high level of fairness & honesty
                with our customers.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="row">
            <div class="col-md">
              <b-img-lazy
                rounded
                src="~/assets/img/pexels-6.jpg"
                alt=""
                class="item"
              ></b-img-lazy>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="mt-5">
      <div class="row">
        <div class="col-md">
          <h4><span class="text-danger font-weight-bold">What </span> We Do</h4>
        </div>
      </div>
    </div>

    <div class="mt-5">
      <OurServiceIndex></OurServiceIndex>
    </div>

    <div class="mt-5">
      <div class="row">
        <div class="col-md">
          <h4>Our <span class="text-danger font-weight-bold">Client </span></h4>
        </div>
      </div>
    </div>
    <div class="mt-5">
      <OurClient></OurClient>
    </div>

    <div class="mt-5">
      <div class="row">
        <div class="col-md">
          <h4>Our <span class="text-danger font-weight-bold">Brands </span></h4>
        </div>
      </div>
    </div>
    <div class="mt-5">
      <OurBrand></OurBrand>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {}
  },
}
</script>
<style scoped>
.item {
  width: 100%;
  height: 100%;
  object-fit: scale-down;
}
</style>
