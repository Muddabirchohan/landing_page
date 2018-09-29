<template>
  <div>
    <div class="nav">
      <b-navbar
        toggleable
        type="light"
        variant="light">
        <b-navbar-toggle
          target="nav_text_collapse"/>
        <!-- <b-navbar-brand>BootstrapVue</b-navbar-brand> -->
        <b-collapse
          id="nav_text_collapse"
          is-nav>
          <b-navbar-nav>
            <nuxt-link to="/home">Home</nuxt-link>
            <nuxt-link to="/features">Features</nuxt-link>
            <nuxt-link to="/packages">Packages</nuxt-link>
            <nuxt-link to="/screenshots">Screenshots</nuxt-link>
            <nuxt-link to="/demoapp">Demo App</nuxt-link>
            <nuxt-link to="/demowebapp">Demo Web App</nuxt-link>
            <nuxt-link to="/contactus">Contact us</nuxt-link>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

<style>
.nav{
float: right;
margin-top: 20px;
padding-left: 20px;
background-color: cornflowerblue;
}
</style>
