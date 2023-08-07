<template>
  <div class="header d-flex align-center justify-space-between">
    <img height="41.93px" src="@/assets/images/logo-study2u.svg" alt="logo">
    <div class="d-flex align-center">
      <div class="nav-header d-flex align-center pr-4 mr-4">
        <nuxt-link class="semibold-subtitle mr-7" to="">
          Institution
        </nuxt-link>
        <nuxt-link class="semibold-subtitle mr-7" to="">
          Course
        </nuxt-link>
        <nuxt-link class="semibold-subtitle" to="">
          Mentor Connect
        </nuxt-link>
      </div>
      <div>
        <nuxt-link class="semibold-subtitle d-flex align-center" to="">
          <img class="mr-2" src="@/assets/icons/user-circle.svg" alt="user-circle">
          Sign In
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
  .header {
    background: $white;
    padding: 19px 0;

    .nav-header {
      height: 40px;
      border-right: 1px solid $dark-grey;

    }

    a {
      text-decoration: none;
      color: $black !important;
    }
  }
</style>