<template>
<b-row class="navbar-container m-0">
  <b-col class="mx-auto">
    <b-navbar class="navbar mx-auto p-0 m-0">
    <b-nav>
      <b-nav-item active class="b-nav-item" href="#yak1">Introduction</b-nav-item>
      <b-nav-item class="b-nav-item" href="#yak2">First Section</b-nav-item>
      <b-nav-item class="b-nav-item" href="#yak3">Second Section</b-nav-item>
      <b-nav-item class="b-nav-item" href="#yak4">Get started</b-nav-item>
    </b-nav>
  </b-navbar>
  </b-col>
  </b-row>
</template>

<script>
export default {

}
</script>

<style>
.navbar-container {
  position: sticky!important;
  top: 0;
  z-index: 1000;
}
.nav-item:hover {
  background-color: rgba(222, 222, 222, 0.25);
  }

  .navbar {
    color: #636363;
    text-decoration: none;
    width: 64em;
    max-width: calc(100% - 4em);
    background-color: #f7f7f7;
    border-top-left-radius: 0.25em;
    border-top-right-radius: 0.25em;
    cursor: default;
    text-align: center;
    font-family: 'Source Sans Pro', sans-serif;
    justify-content:center!important;
    font-weight: 300;
    position: sticky!important;
    top: 0;
    min-height: 3em;
    z-index: 1000;
  }

li.b-nav-item > a {
  color: #636363!important;
  font-size: 12pt;
  white-space: nowrap;
}
@media (max-width: 1200px) {
  .navbar {
    display: none!important;
  }
}
</style>
