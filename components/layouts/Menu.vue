<template>
  <b-navbar toggleable="lg" style="background: #eaeaea">
    <b-navbar-brand href="#"
      ><span class="text-danger"
        >United<span class="font-weight-bold">Engineering</span></span
      >
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <NuxtLink to="/" class="nav-link">Home</NuxtLink>
        <NuxtLink to="/about" class="nav-link">About Us</NuxtLink>

        <b-nav-item-dropdown text="Our Product" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item href="#">Our Service</b-nav-item>
        <b-nav-item href="#">Contact us</b-nav-item>
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
