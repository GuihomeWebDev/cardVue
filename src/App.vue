<template>
  <div id="app">
    <b-navbar type="dark" variant="dark">
      <b-navbar-brand href="#">Guihome</b-navbar-brand>
      <b-navbar-nav>
        <b-nav-item href="/">Accueil</b-nav-item>
        <b-nav-item href="/about">A propos</b-nav-item>
      </b-navbar-nav>
    </b-navbar>

    <div class="contenu container">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style></style>
