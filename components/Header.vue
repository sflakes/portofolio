<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="transparent">
      <!-- <b-navbar-brand href="/">FATKHURIFAZRI</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle> -->

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-navbar-nav>
            <nuxt-link class="nav-link" to="/">Home</nuxt-link>
            <nuxt-link class="nav-link" to="/Works">Works</nuxt-link>
            <nuxt-link
              class="nav-link"
              to="/HireMe"
              
              >Contact</nuxt-link
            >
            <!-- <b-nav-item href="#" disabled>Disabled</b-nav-item> -->
          </b-navbar-nav>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style >
.nuxt-link-exact-active {
  background-color: #6c63ff;
  border-radius: 30% 70% 70% 30% / 30% 30% 70% 70%;
}
.navbar {
  padding-top: 5%;
  padding-left: 0;
  color: white;
}
</style>