<template>
  <div class="container">
    <div class="dropdown">
      <button
        id="dropdownMenuButton"
        class="btn btn-secondary dropdown-toggle"
        type="button"
        data-toggle="dropdown"
        aria-haspopup="true"
        aria-expanded="true"
        @mouseover="isOpen = true"
        @mouseleave="isOpen = false"
      >
        Dropdown button
      </button>
      <div class="dropdown-menu" :class="{ show: isOpen }" aria-labelledby="dropdownMenuButton">
        <a class="dropdown-item" href="#">Action</a>
        <a class="dropdown-item" href="#">Another action</a>
        <a class="dropdown-item" href="#">Something else here</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    isOpen: false
  })
}
</script>

<style>

</style>
