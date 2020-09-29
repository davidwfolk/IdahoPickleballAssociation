<template>
  <div class="">
    <div id="">
      <div class="jumbotron jumbotron-fluid mb-0">
        <div class="container text-center">
          <h1
            class="title display-3 text-center pt-5 mt-0"
            style="font-weight: 100"
          >
            Idaho
            <strong style="font-weight: 600">Pickleball</strong> Association
          </h1>
          <img
            src="../assets/pblogo.png"
            class="text-center"
            style="width: 40%"
          />
          <h1 class="text-center display-5 mt-3" style="font-weight: 200">
            We're kind of a <strong style="font-weight: 600">big dill</strong>.
          </h1>
          <div class="col-12">
            <button class="btn btn-success mt-4 font-weight-bold">Learn More</button>
          </div>
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
.jumbotron {
  background: 
  linear-gradient(
    180deg,
    rgba(72, 163, 184, 1) 0%,
    rgba(72, 163, 184, 1) 54%,
    rgba(29, 83, 165, 1) 100%
  );
  // url(../assets/bgnet-hero.png);
  background-repeat: no-repeat;
  // background-attachment: fixed;
  color: white !important;
  width: 100vw;
  padding-top: 0px;
}

.title {
  margin-top: 4vh;
}
.text_margin {
  width: 70vw;
  margin: 0 auto;
}

.dill {
  font-family: Marker Felt, fantasy;
}
</style>