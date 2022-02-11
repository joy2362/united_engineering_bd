<template>
  <b-navbar toggleable="lg" style="background: #eaeaea">
    <NuxtLink to="/" class="navbar-brand">
      <b-img-lazy
        rounded
        src="~/assets/img/logo/main.png"
        alt=""
        style="height: 70px; witdth: 100%; object-fit: cover"
      ></b-img-lazy>
    </NuxtLink>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <NuxtLink to="/" class="nav-link">Home</NuxtLink>
        <NuxtLink to="/about-us" class="nav-link">About Us</NuxtLink>

        <b-nav-item-dropdown text="Our Product" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item href="#">Our Service</b-nav-item>
        <NuxtLink to="/contact-us" class="nav-link">Contact us</NuxtLink>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
  name: 'MenuItem',
}
</script>

<style scoped></style>
