<template>
  <div class="container">
    <nav class="navbar navbar-light bg-light flex-row-reverse">
      <div class="d-flex flex-row align-items-center">
        <div class="dropdown">
          <a
            id="dropdownMenuLink"
            class="btn btn-secondary dropdown-toggle"
            href="#"
            role="button"
            data-toggle="dropdown"
            aria-haspopup="true"
            aria-expanded="false"
          >
            full name
          </a>
          <div class="dropdown-menu" aria-labelledby="dropdownMenuLink">
            <a class="dropdown-item" href="#">Action</a>
            <a class="dropdown-item" href="#">Another action</a>
            <a class="dropdown-item" href="#">Something else here</a>
          </div>
        </div>
        <font-awesome-icon :icon="['fas', 'user-circle']" class="fa-2x ml-2" />
        <font-awesome-icon :icon="['fas', 'question-circle']" class="fa-2x ml-2" />
      </div>
      <div>
        <font-awesome-icon :icon="['fas', 'bars']" class="fa-2x" />
      </div>
    </nav>
    <div class="row">
      <div class="col-10" />
      <div class="col-2" />
    </div>
  </div>
  </div>
</template>

<script>
export default {}
</script>

<style>

</style>
