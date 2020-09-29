<template>
  <div class="bg">
    <b-card no-body>
      <b-card-header header-tag="nav">
        <b-nav card-header tabs>
          <b-nav-item @click="findCourt()">Find a Court</b-nav-item>
          <b-nav-item @click="members()">Connect with Members</b-nav-item>
          <b-nav-item>Disabled</b-nav-item>
        </b-nav>
      </b-card-header>
      <b-card-body class="text-center m-0 p-0">
        <div v-if="!active">
          <Carousel />
        </div>
        <div v-else></div>
        <div v-if="!member" class="memberhidden">
          <h1>test</h1>
        </div>
        <div v-else></div>
      </b-card-body>
    </b-card>
  </div>
</template>

<script>
import Carousel from "../components/Carousel"
export default {
  data() {
    return {
      active: false,
      member: false,
    };
  },
  methods: {
    findCourt() {
      this.active = false
      this.member = true
    },
    members() {
      this.member = false
      this.active = true
    },
  },
  components: {
    Carousel,
  }
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

.memberhidden {
  visibility: hidden;
}
</style>