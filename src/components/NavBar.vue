<template>
 <div>
  <b-navbar type="dark" variant="primary" toggleable>
    <b-navbar-toggle target="nav_dropdown_collapse"></b-navbar-toggle>
    <b-collapse is-nav id="nav_dropdown_collapse">
      <b-navbar-nav>
        <b-nav-item :to="{name: 'all-galleries'}">All Galeries</b-nav-item>
        <b-nav-item :to="{name: 'login'}">Login</b-nav-item>
        <b-nav-item :to="{name: 'register'}">Register</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {
  name: 'NavBar',
  
}
</script>
