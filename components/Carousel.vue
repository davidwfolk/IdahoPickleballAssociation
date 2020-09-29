<template>
  <div class="bg">
    <div class="container">
      <div class="row py-5">
        <div class="col-md-8 order-1 order-md-0 col-12 px-0">
          <b-carousel
            id="carousel-fade"
            style="text-shadow: 0px 0px 2px #000"
            fade
            indicators
            img-width="724"
            img-height="480"
          >
            <b-carousel-slide
              caption="First slide"
              img-src="https://picsum.photos/1024/480/?image=10"
            ></b-carousel-slide>
            <b-carousel-slide
              caption="Second Slide"
              img-src="https://picsum.photos/1024/480/?image=12"
            ></b-carousel-slide>
            <b-carousel-slide
              caption="Third Slide"
              img-src="https://picsum.photos/1024/480/?image=22"
            ></b-carousel-slide>
          </b-carousel>
        </div>
        <div
          class="col-12 col-md-4 order-0 order-md-1 bg-transparent text-center my-0"
        >
          <h1 class="title blue pt-4 text-center" style="font-weight: 100">
            Idaho
            <strong style="font-weight: 600">Pickleball</strong> Association
          </h1>
          <h3 class="text-white pb-2">Find a game now!</h3>
          <b-button variant="outline-light" class="btn-circle btn-xl mb-5 font-weight-bold"
            ><strong>FIND GAME</strong></b-button
          >
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
.bg {
  background: linear-gradient(
    0deg,
    rgb(85, 168, 70) 10%,
    rgb(85, 168, 70, 0.8) 60%,
    rgba(29, 83, 165, 0.2) 100%
  );
}

.blue {
  color:rgb(29, 83, 165,);
  text-shadow: 2px 2px 3px #fff;

}
.btn-circle.btn-xl {
  width: 70px;
  height: 70px;
  padding: 10px 16px;
  border-radius: 35px;
  font-size: 12px;
  text-align: center;
}
</style>