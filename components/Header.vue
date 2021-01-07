<template>
  <b-navbar toggleable="lg">
    <b-navbar-brand href="#" class="text-primary font-weight-bold"
      >Landkit.</b-navbar-brand
    >

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-button size="sm" variant="text" class="mx-3" type="submit"
          >Products</b-button
        >
        <b-button size="sm" variant="text" class="mx-3" type="submit"
          >Developers</b-button
        >
        <b-button size="sm" variant="text" class="mx-3" type="submit"
          >Company</b-button
        >
        <b-button size="sm" variant="text" class="mx-3" type="submit"
          >Pricing</b-button
        >
      </b-navbar-nav>

      <b-navbar-nav class="ml-auto">
        <b-button size="sm" variant="text" class="my-2 my-sm-0" type="submit"
          >Login</b-button
        >
        <b-button size="sm" variant="primary" class="my-2 my-sm-0" type="submit"
          >Sign In</b-button
        >
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped></style>
