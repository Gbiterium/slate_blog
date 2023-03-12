<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <nav
    id="navbar"
    class="  navbar navbar-expand-lg pl-0
        "
    :class="{ scrolling_active: scrollPosition > 100 }"
    @scroll="scrollHandler"
  >
    <div
      class="container-fluid px-lg-4 p-0 d-flex align-items-center
        flex-wrap
        justify-content-between "
    >
      <nuxt-link class="pl-2" to="/">
        <img src="@/assets/img/logo.png">
      </nuxt-link>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarResponsive"
        aria-controls="navbarResponsive"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="30"
          height="30"
          viewBox="0 0 30 30"
          role="img"
          focusable="false"
        >
          <title>Menu</title>
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-miterlimit="10"
            stroke-width="2"
            d="M4 7h22M4 15h22M4 23h22"
          />
        </svg>
      </button>
      <div id="navbarResponsive" class="navbar-nav align-items-center collapse navbar-collapse">
        <li class="nav-item">
          <nuxt-link to="/about-us" class="nav-link text-dark">
            About Us
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link to="/categories" class="nav-link text-dark">
            Categories
          </nuxt-link>
        </li>
        <li class="nav-item mr-lg-5">
          <nuxt-link to="/resources" class="nav-link text-dark">
            Resources
          </nuxt-link>
        </li>
        <div class="d-flex align-items-center search ml-lg-5 navbar-nav">
          <input class="form-control mr-sm-2 mr-4 search-input" type="search" placeholder="Search" aria-label="Search">
          <b-icon-search class="search-icon ml-3" />
          <button class="btn btn-primary mr-lg-3" type="submit">
            Login
          </button>
          <div class="social-icons mr-3 text-blue">
            <b-icon-facebook />
          </div>
          <div class="social-icons mr-3 text-blue">
            <b-icon-twitter />
          </div>
          <div class="social-icons text-blue">
            <b-icon-instagram />
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data () {
    return {
      scrollPosition: 0
    }
  },
  mounted () {
    window.addEventListener('scroll', this.updateScroll)
  },
  methods: {
    scrollHandler () {
      // eslint-disable-next-line no-unused-expressions
      this.scrollPosition
    },
    updateScroll () {
      this.scrollPosition = window.scrollY
    }
  }
}
</script>

<style>
.search-input {
  border-radius: 20px;
  border: 2px solid #1070B7;
}
.search {
  position: relative;
}
.social-icons {
  width: 40px;
  border-radius: 50%;
}
.search-icon{
  position: absolute;
  font-size: 16px;
}
.search input {
  padding-left: calc(20px + 10px + 0.4rem);
}
.navbar-collapse {
  flex-grow: 0 !important;
}
#navbar {
  position: fixed;
  top: 0;
  left: 0;
  z-index: 1030;
  background: #F5F6F7;
  width: 100%;
}
.scrolling_active {
    background-color: #F5F6F7;
    color: black;
    box-shadow: 0 3px 1rem rgba(0, 0, 0, 0.1);
  }
</style>
