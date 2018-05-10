<template>
  <nav class="navbar is-dark" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a href="/" class="navbar-item">RC</a>
      <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>
    <div class="navbar-menu">
      <div class="navbar-start">
        <a href="/" class="navbar-item">About</a>
        <a href="/" class="navbar-item">Projects</a>
        <a href="/" class="navbar-item">Contact</a>
      </div>
      <div class="navbar-end">
        <a href="https://www.twitter.com/RogerClayton" class="navbar-item">
          <i class="fa fa-twitter fa-lg"></i>
        </a>
        <a href="https://www.linkedin.com/in/roger-clayton" class="navbar-item">
          <i class="fa fa-linkedin fa-lg"></i>
        </a>
        <a href="https://www.github.com/radiohegel" class="navbar-item">
          <i class="fa fa-github fa-lg"></i>
        </a>
      </div>
    </div>
  </nav>
</template>

<script>
  export default {
    name: "NavBar"
  }
</script>

<style>

</style>