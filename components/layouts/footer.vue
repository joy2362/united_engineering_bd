<template>
  <footer style="background: #eaeaea">
    <div class="mt-5">
      <div class="row pt-3">
        <div class="col-md-4 text-center">
          <h5>About us</h5>
          <p class="text-justify">
            United Engineering has customized services which helps Bangladeshi
            readymade Garments Manufacturers to Comply with ACCORD & ALLIANCE.
            During this time FIRE SAFETY, ELECTRICAL SAFETY & Micro control have
            become specialists in planned preventative maintenance as well as
            Installations.
          </p>
        </div>
        <div class="col-md-4 text-center">
          <h5>Quick Links</h5>
          <NuxtLink to="/about" class="nav-link">About Us</NuxtLink>
          <NuxtLink to="/about" class="nav-link">Our services</NuxtLink>
          <NuxtLink to="/about" class="nav-link">Contact Us</NuxtLink>
        </div>
        <div class="col-md-4 text-center">
          <h5>Contact Info</h5>
          <p>Address: 145/3-1 Matikhata Dhaka Cantonment Dhaka-1206.</p>
          <p>Email: admin@unitedengineeringbd.com</p>
          <p>Business Hours: Saturday-Thursday 9am to 6pm.</p>
        </div>
      </div>
      <div class="row">
        <div class="col-md text-center p-3">
          Develop with <span class="text-danger">&#9829;</span> by
          <a href="https://github.com/joy2362" target="_blank">
            Abdullah Zahid</a
          >
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterSection',
}
</script>

<style></style>
