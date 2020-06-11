<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar variant="faded" type="light">
        <b-navbar-brand href="#">
          <img src="../assets/logo.png" alt="Kitten" id="logo">
        </b-navbar-brand>
      </b-navbar>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-form-input 
            size="sm" 
            class="mr-sm-2" 
            placeholder="Search"></b-form-input>
            <b-button size="sm" class="my-2 my-sm-0" type="submit">
              Search
            </b-button>
          </b-nav-form>
 
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>


        <b-navbar variant="faded" type="light">
            <div>
            <b-nav vertical class="w-25">
                <b-nav-item active>Active</b-nav-item>
                <b-nav-item>Link</b-nav-item>
                <b-nav-item>Another Link</b-nav-item>
                <b-nav-item disabled>Disabled</b-nav-item>
            </b-nav>
            </div> 
        </b-navbar>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "Footer",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#logo {
  width: 150px;
  height: 150px;
}
</style>