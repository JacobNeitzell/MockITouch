<template>
  <div class="container-fluid position relative">
    <div class="row">
      <div
        class="col-lg-12 col-md-6 d-flex justify-content-center flex-column border-0 rounded position-relative p-1 bg-dark">
        <h1 class="d-flex justify-content-center">ACCOUNT</h1>
        Testing commit
        Test 2
      </div>
    </div>

  </div>
</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;

  .home-card {
    width: 50vw;

    >img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
