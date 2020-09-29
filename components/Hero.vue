<template>
  <div class="">
    <div id="">
      <div class="jumbotron jumbotron-fluid mb-0">
        <div class="container text-center">
          <h1
            class="title display-3 text-center pt-2 mt-0"
            style="font-weight: 100"
          >
            Idaho
            <strong style="font-weight: 600">Pickleball</strong> Association
          </h1>
          <!-- <img
            src="../assets/pblogo.png"
            class="text-center"
            style="width: 40%"
          /> -->

          <b-carousel
            id="carousel-fade"
            style="text-shadow: 0px 0px 2px #000; width: 65vw"
            fade
            indicators
            img-width="524"
            img-height="280"
            class="mx-auto"
          >
            <b-carousel-slide
              caption=""
              img-src="../assets/pblogo-carousel.png"
            ></b-carousel-slide>
            <b-carousel-slide
              caption=""
              img-src="../assets/pb1.png"
            ></b-carousel-slide>
            <b-carousel-slide
              caption=""
              class="text"
              img-src="../assets/pb2.png"
            ></b-carousel-slide>
          </b-carousel>
          <h1 class="text-center display-5 mt-3" style="font-weight: 200">
            We're kind of a <strong style="font-weight: 600">big dill</strong>.
          </h1>
          <div class="col-12">
            <button class="btn btn-success mt-4 font-weight-bold">
              Join Now - It's Free!
            </button>
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
  background: linear-gradient(
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

.text{
  color: rgb(29, 83, 165)
}
</style>