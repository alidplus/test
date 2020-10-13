<template>
  <div class="container">
    <div class="row">
      <div class="col-12">
        <nav-bar />
      </div>
      <div class="col-12 col-md-6 col-lg-9">
        Main
      </div>
      <div class="col-12 col-md-6 col-lg-3">
        <side-bar />
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from '~/components/Aidin/NavBar'
import SideBar from '~/components/Aidin/SideBar'
export default {
  components: {
    NavBar,
    SideBar
  }
}
</script>

<style>

</style>
