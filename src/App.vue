<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>

    <router-view/>
  </div>
</template>

<style lang="scss">
@import 'assets/sass/app';
@import 'assets/css/all.css';
@import 'assets/css/bootstrap.min.css';
</style>
