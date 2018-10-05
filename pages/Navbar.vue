<template>
  <b-navbar
    type="dark"
    toggleable="md">

    <b-navbar-toggle
      target="nav_collapse"/>

    <b-collapse
      id="nav_collapse"
      is-nav >

      <b-navbar-nav>
        <b-nav-item
          to="home"
          style="color: white;">Home</b-nav-item>
        <b-nav-item
          v-scroll-to="'#features'"
          style="color: white;">Features</b-nav-item>
        <b-nav-item
          v-scroll-to="'#screenshots'"
          style="color: white;">Screenshots</b-nav-item>
        <b-nav-item
          v-scroll-to="'#about'"
          style="color: white;">About-us</b-nav-item>
        <b-nav-item
          v-scroll-to="'#demowebapp'"
          style="color: white;">Demo WebApp</b-nav-item>
        <b-nav-item
          v-scroll-to="'#packages'"
          style="color: white;">packages</b-nav-item>
        <b-nav-item
          v-scroll-to="'#contactus'"
          style="color: white;">contact-us</b-nav-item>
      </b-navbar-nav>

    </b-collapse>
  </b-navbar>
</template>

