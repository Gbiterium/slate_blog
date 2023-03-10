<template>
  <div class="landing-page">
    <section class="header-banner">
      <div class="header-content">
        <div class="left-wrapper">
          <div class="left-wrapper-content">
            <span class="text-uppercase text-blue">Top News</span>
            <h3 class="font-weight-bold">
              Digital learning and its incorporation into early education.
            </h3>
            <!-- <div class="underline-abs">
              <img src="@/assets/img/underline.png" alt="">
            </div> -->
            <p class="text-light">
              Thur, January 12, 2023 - 9:15 am
            </p>
            <button type="button" class="btn btn-outline-primary read-more" @click.prevent="readmore">
              Read More <b-icon-arrow-right-short />
            </button>
          </div>
        </div>
        <div class="right-wrapper">
          <div class="person-abs">
            <img src="@/assets/img/landing.png" alt="">
          </div>
          <div class="img-abs">
            <img
              src="@/assets/img/Vector.png"
              alt=""
            >
          </div>
          <div class="dot-abs mb-lg-4">
            <img
              src="@/assets/img/dot.png"
              alt=""
            >
          </div>
        </div>
      </div>
    </section>
    <section class="featured-post">
      <div class="featured-post-content">
        <div class="featured-header my-5">
          <h4 class="font-weight-bold">
            Featured Posts
          </h4>
          <nuxt-link to="/popular-topics" class="float-right text-dark text-decoration-none">View All</nuxt-link>
        </div>
        <div class="row">
          <div class="col-md-7 box">
            <div class="card">
              <div class="card-body">
                <div>
                  <img src="@/assets/img/waec.png">
                </div>
                <div class="pt-4 px-4">
                  <h5 class="font-weight-bold">
                    West African Examination Council (WAEC) releases 2023
                    results, as Anambra take Lead.
                  </h5>
                  <p class="text-light">
                    Lorem ipsum dolor sit amet consectetur. Erat nisl semper
                    aenean duis purus et id sem. Malesuada quam porta feugiat
                    ultrices id cras imperdiet. Viverra donec malesuada nec
                    pellentesque. Iaculis urna mus semper scelerisque. Porta
                    venenatis lacinia commodo leo non laoreet. Suspendisse vitae
                    in nulla lobortis gravida adipiscing. Lorem ipsum dolor sit
                    amet consectetur. Erat nisl semper aenean duis purus et id
                    sem. Malesuada quam porta feugiat ultrices id cras
                    imperdiet. Viverra donec malesuada nec pellentesque. Iaculis
                    urna mus semper scelerisque. Porta venenatis lacinia commodo
                    leo non laoreet. Suspendisse vitae in nulla lobortis gravida
                    adipiscing.
                  </p>
                  <p class="text-blue">
                    Thur, January 12, 2023 - 9:15 am
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-5">
            <div class="card shadow border-0">
              <div class="card-body d-flex">
                <div>
                  <img src="@/assets/img/image 3.png" class="featured-post-img1" alt="" width="240" height="292">
                </div>
                <div class="p-4 featured1">
                  <h5 class="font-weight-bold">
                    The Future of Education
                  </h5>
                  <p class="text-light mt-2">
                    It if sometimes furnished unwilling as additions so.
                    Blessing resolved peculiar fat graceful ham. Sussex on at
                    really ladies in as elinor. Sir sex opinions age properly
                    extended. Advice branch.
                  </p>
                  <p class="text-blue">
                    Thur, January 12, 2023 - 9:15 am
                  </p>
                </div>
              </div>
            </div>
            <div class="card shadow border-0 mt-5">
              <div class="card-body d-flex">
                <div>
                  <img src="@/assets/img/image 2.png" class="featured-post-img" alt="" width="240" height="318">
                </div>
                <div class="p-4 featured2">
                  <h5 class="font-weight-bold">
                    How to incorporate children to home school.
                  </h5>
                  <p class="text-light mt-2">
                    It if sometimes furnished unwilling as additions so.
                    Blessing resolved peculiar fat graceful ham. Sussex on at
                    really ladies in as elinor. Sir sex opinions age properly
                    extended. Advice branch
                  </p>
                  <p class="text-blue">
                    Thur, January 12, 2023 - 9:15 am
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <Posts />
      </div>
    </section>
    <RegisterSchool />
    <section class="section-4">
      <div>
        <h4 class="my-5 font-weight-bold">
          Articles and Books for the Month
        </h4>
        <div class="row articles">
          <div class="col-md-4 box">
            <img src="@/assets/img/card.png" alt="">
          </div>
          <div class="col-md-4 box">
            <img src="@/assets/img/swim.png" alt="">
          </div>
          <div class="col-md-4">
            <img src="@/assets/img/tech.png" alt="">
          </div>
        </div>
      </div>
    </section>
    <PopularTopics />
    <Subscribe />
  </div>
</template>

<script>
export default {
  methods: {
    readmore () {
      this.$router.push('/top-news')
    }
  }
}
</script>

<style scoped>
.featured-post img, .section-4 img{
  width: 100%;
  height: auto
}
.read-more{
  background: transparent;
}
.school-desc button{
  color: #EE6A5F;
}
</style>
