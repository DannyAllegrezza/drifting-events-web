<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <!-- Site Logo -->
      <a href="#" class="navbar-item">
        <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28" alt>
      </a>
      <!-- Hamburger menu -->
      <a
        class="navbar-burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample"
        role="button"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div class="navbar-menu" id="navbarBasicExample">
      <!-- .navbar-start :: the left part of the menu, which appears next to the navbar brand on desktop -->
      <div class="navbar-start">
        <a class="navbar-item">Home</a>
        <a class="navbar-item">About</a>
        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">More</a>
          <div class="navbar-dropdown">
            <a class="navbar-item">About</a>
            <a class="navbar-item">Jobs</a>
            <a class="navbar-item">Contact</a>
            <hr class="navbar-divider">
            <a class="navbar-item">Report an issue</a>
          </div>
        </div>
        <b-input icon="search" type="search" placeholder="Search..."></b-input>
      </div>

      <div class="navbar-end">
        <div class="navbar-item">
          <div class="buttons">
            <a class="button is-primary">
              <strong>Sign up</strong>
            </a>
            <a class="button is-light">Log in</a>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {}
</script>
