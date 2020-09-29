<template>
  <div>
    <div>
      <div class="bg-dark text-white border-0">
        <div>
          <b-nav>
            <div class="col-6">
              <h6 class="text-center th mt-2">Idaho Pickleball Association</h6>
            </div>
            <div class="col-6 text-right">

            <div class="text-center mt-1"><span class="icon"><font-awesome-icon :icon="['fab', 'facebook']"/></span>
            <span class="icon mx-3"><font-awesome-icon :icon="['fab', 'youtube']"/></span>
            <span class="icon"><font-awesome-icon :icon="['fab', 'instagram']"/></span>
            </div>
            
            </div>
          </b-nav>
        </div>
      </div>
    </div>
    <div>
      <b-navbar toggleable="lg" type="dark" variant="info">
        <b-navbar-brand href="#"
          ><img
            src="../assets/pblogo.png"
            class="img-fluid"
            style="width: 50px"
        /></b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <nav-item class="font-weight-bold text-white pl-3" href="#"
              >Link</nav-item
            >
          </b-navbar-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-nav-form>
              <b-form-input
                size="sm"
                class="mr-sm-2"
                placeholder="Search"
              ></b-form-input>
              <b-button size="sm" class="my-2 my-sm-0" type="submit"
                >Search</b-button
              >
            </b-nav-form>

            <b-nav-item-dropdown right>
              <!-- Using 'button-content' slot -->
              <template v-slot:button-content>
                <em>User</em>
              </template>
              <b-dropdown-item href="#">Profile</b-dropdown-item>
              <b-dropdown-item href="#">Sign Out</b-dropdown-item>
            </b-nav-item-dropdown>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.th {
  font-size: 12px;
}
</style>