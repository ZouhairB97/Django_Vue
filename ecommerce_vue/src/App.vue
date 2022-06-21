<template>
  <div id="app">
    <div id="wrapper">
      <nav class="navbar is-dark">
        <div class="navbar-brand">
          <router-link to="/" class="navbar-item"><strong>Ecommerce</strong></router-link>
          
          <a class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbar-menu">
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
            <span aria-hidden="true"></span>
          </a>
        </div>
        <a>h</a>
        <div class="navbar-menu" id="navbar-menu"></div>
      </nav>
      <router-view/>
    </div>
  </div>
</template>

<style lang="scss">
@import '../node_modules/bulma';
</style>
