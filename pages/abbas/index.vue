<template>
  <div class="container">
    <div class="row">
      <div class="col-12 border">
        <nav-bar />
      </div>
      <div class="col-9 border">
        main
      </div>
      <div class="col-3 border">
        <side-bar />
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from '~/components/abbas/NavBar'
import SideBar from '~/components/abbas/SideBar'

export default {
  components: {
    NavBar,
    SideBar
  }
}
</script>

<style>

</style>
