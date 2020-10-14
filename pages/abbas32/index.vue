<template>
  <div class="container">
    <nav class="navbar navbar-light bg-light">
      <div class="d-flex flex-row align-items-center">
        <a class="navbar-brand">
          <font-awesome-icon :icon="['fa', 'sign-in-alt']" />
          <i class="fas fa-sign-in-alt" />
          ورود
        </a>
      </div>
    </nav>
    <div>
      <h1 class="my-5 text-center">
        عنوان سایت
        <img src="https://seeklogo.com/images/T/Test-logo-37F8EF5B80-seeklogo.com.png" alt="logo" width="50">
      </h1>
    </div>
    <div class="row mt-5">
      <div class="col">
        <div class="card m-3 extra-rounded">
          <img src="/valiball.png" class="card-img-top" alt="valiball">
        </div>
      </div>
      <div class="col">
        <div class="card m-3 extra-rounded">
          <img src="/body bilding.png" class="card-img-top" alt="body bilding">
        </div>
      </div>
      <div class="col">
        <div class="card m-3 extra-rounded">
          <img src="/ball.jpg" class="card-img-top" alt="footbal">
        </div>
      </div>
      <div class="col">
        <div class="card m-3 extra-rounded">
          <img src="/Mountain climbing.jpg" class="card-img-top" alt="Mountain climbing">
        </div>
      </div>
    </div>
    <div class="d-flex justify-content-center  mt-5">
      <button type="button" class="btn btn-light w-25">
        قوانين و مقررات
      </button>

      <button type="button" class="btn btn-light w-25">
        سوالات متداول
      </button>

      <button type="button" class="btn btn-light w-25">
        تماس با ما
      </button>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>

</style>
