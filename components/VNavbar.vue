<template>
  <b-navbar toggleable="sm">
    <b-navbar-brand to="/">
      <img src="@/static/edgeprop.png" alt="edgeprop logo" class="img-logo" />
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item to="/" class="mr-48" exact exact-active-class="active"
          >Home</b-nav-item
        >
        <b-nav-item to="/about">About</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {}
</script>

<style lang="scss">
.img-logo {
  width: 197.67px;
}
.nav-link {
  font-size: 20px;
  &.active {
    color: 333333, 100%;
    font-weight: 600;
    border-bottom: 3px solid #1a7cd2;
  }
}
</style>
