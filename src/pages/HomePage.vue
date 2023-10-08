<template>
  <div class="container-fluid  ">
    <div class="row justify-content-center p-2 m-2">
      <div
        class="col-md-6 d-flex justify-content-center flex-column border-0 rounded position-relative p-1 bg-dark elevation-4">
        <h1 class="d-flex justify-content-center">InTouch</h1>
        <div class="text-center">
          <img src="../assets/img/Jakeface.png" class="img-fluid rounded-circle text-end" alt="...">
        </div>
        <h2 class="d-flex justify-content-center">Sign In</h2>
        <div class="mb-3">
          <label for="exampleFormControlInput1" class="form-label">Email address</label>
          <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
          <div class="col-auto">
            <label for="inputPassword6" class="col-form-label">Password</label>
          </div>
          <div class="col-auto">
            <input type="password" id="inputPassword6" class="form-control" aria-describedby="passwordHelpInline">
          </div>
          <div class="col-auto">
            <span id="passwordHelpInline" class="form-text text-light">
              Must be 8-20 characters long.
            </span>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" value="Remember Me" id="flexCheckChecked" checked>
            <label class="form-check-label" for="flexCheckChecked">
              Remember Me
            </label>
            <label class="selectable float-end">Forgot Password</label>
          </div>
        </div>
        <input class="btn btn-dark " type="submit" value="Submit">
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

    >image {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }

  .prof {
    height: 45px;
    max-width: 50%;
    width: 50%;
    object-fit: fill;
    object-position: center;
  }
}
</style>
