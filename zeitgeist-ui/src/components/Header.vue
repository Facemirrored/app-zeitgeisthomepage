<template>
  <div>
        <b-navbar class="bg-transparent navbar-dark navbar navbar-expand-lg" fixed="true">
          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <!-- Left aligned nav items  -->
            <b-navbar-nav>
              <b-nav-item href="#">Home</b-nav-item>
              <b-nav-item href="#">Link</b-nav-item>
            </b-navbar-nav>

            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto">
              <b-nav-form>
                <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
                <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
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
</template>

<script>
  export default {
    name: "Header",
  }
</script>

<style scoped>
  .nav {
  }
</style>