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

  <b-navbar variant="faded" type="light">
    <b-navbar-brand href="#">
      <b-icon icon="person"></b-icon>
    </b-navbar-brand>
  </b-navbar>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
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
