<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div class="footer">
    <div
      class="footer-content py-5 d-flex justify-content-center align-items-center"
    >
      <div>
        <div class="d-flex justify-content-center align-items-center">
          <img src="@/assets/img/logo-white.png" alt="">
        </div>
        <div class="d-flex justify-content-center my-3">
          <nav class="nav align-items-center text-white">
            <li class="nav-item">
              <nuxt-link to="/" class="nav-link text-white">
                Home
              </nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/categories" class="nav-link text-white">
                Categories
              </nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/resources" class="nav-link text-white">
                Resources
              </nuxt-link>
            </li>
            <li class="nav-item">
              <span class="nav-link"> Donate </span>
            </li>
            <li class="nav-item">
              <span class="nav-link">Contact us</span>
            </li>
          </nav>
        </div>
        <p class="text-white text-center px-3">
          Lörem ipsum od ohet dilogi. Bell trabel, samuligt, ohöbel utom diska.
          Jinesade bel när feras redorade i belogi. FAR paratyp i
          muvåning, och pesask vyfisat. Viktiga poddradio har un mad och inde.
        </p>
        <div class="d-flex justify-content-center mb-4">
          <nav class="nav icons align-items-center text-white">
            <li class="nav-item">
              <span class="nav-link"><b-icon-facebook /></span>
            </li>
            <li class="nav-item">
              <span class="nav-link"><b-icon-twitter /></span>
            </li>
            <li class="nav-item">
              <span class="nav-link"><b-icon-linkedin /></span>
            </li>
            <li class="nav-item">
              <span class="nav-link"><b-icon-instagram /></span>
            </li>
          </nav>
        </div>
      </div>
    </div>
    <div class="left-area bg-pink" />
    <div class="right-area bg-pink" />
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.footer {
  position: relative;
  background: #1070b7;
}
.icons {
  position: absolute;
  bottom: 0;
}
</style>
