<template>
  <div class="emailbg">

    <div class="container">
        <h1 class="text-white text-center pt-5">Sign Up for Our Newsletter</h1>
      <div class="input-group mt-5 mb-3 text-center">
        <input
          type="text"
          class="form-control"
          placeholder="Recipient's username"
          aria-label="Recipient's username"
          aria-describedby="button-addon2"
        />
        <div class="input-group-append">
          <button
            class="btn btn-success mb-5"
            type="button"
            id="button-addon2"
          >
            Button
          </button>
        </div>
      </div>
    </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.emailbg {
  background: 
    linear-gradient(
    rgba(29, 83, 165, 1) 0%,
    rgba(29, 83, 165, 1) 70%,
    rgba(29, 83, 165, .2) 100%);
    // url(../assets/pb-hero.png);
  height:35vh;
}

.bg {
  background: linear-gradient();
}
</style>