<template>
  <div>
    <BaseHeader />
    <div class="categories-page">
      <div class="categories-header d-flex mt-3">
        <div class="mr-4">
          <b-icon-arrow-left-short />
          <span>Back</span>
        </div>
        <span class="text-blue text-decoration-underline">Categories</span>
      </div>
      <div class="categories-content mb-5">
        <h4 class="my-4 font-weight-bold">
          Categories
        </h4>
        <div class="row">
          <div class="col-md-4 box">
            <div class="card border-0">
              <div class="card-body">
                <img src="@/assets/img/education.png" alt="">
                <div class="education">
                  <h4 class="text-uppercase p-3 text-center">
                    education
                  </h4>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 box">
            <div class="card border-0">
              <div class="card-body">
                <img src="@/assets/img/fashion.png" alt="">
                <div class="fashion">
                  <h4 class="text-uppercase p-3 text-center">
                    fashion
                  </h4>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 box">
            <div class="card border-0">
              <div class="card-body">
                <img src="@/assets/img/sport.png" alt="">
                <div class="sport">
                  <h4 class="text-uppercase p-3 text-center">
                    sports
                  </h4>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row mt-3">
          <div class="col-md-4 box">
            <div class="card border-0">
              <div class="card-body">
                <img src="@/assets/img/kiddies.png" alt="">
                <div class="kiddies">
                  <h4 class="text-uppercase p-3 text-center">
                    kiddies
                  </h4>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 box">
            <div class="card border-0">
              <div class="card-body">
                <img src="@/assets/img/entertainment.png" alt="">
                <div class="entertainment">
                  <h4 class="text-uppercase p-3 text-center">
                    entertainment
                  </h4>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 box">
            <div class="card border-0">
              <div class="card-body">
                <img src="@/assets/img/food.png" alt="">
                <div class="food">
                  <h4 class="text-uppercase p-3 text-center">
                    fOOD AND COOKING
                  </h4>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row mt-3">
          <div class="col-md-4 box">
            <div class="card border-0">
              <div class="card-body">
                <img src="@/assets/img/foreign.png" alt="">
                <div class="foreign">
                  <h4 class="text-uppercase p-3 text-center">
                    foreign news
                  </h4>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 box">
            <div class="card border-0">
              <div class="card-body">
                <img src="@/assets/img/politiics.png" alt="">
                <div class="politics">
                  <h4 class="text-uppercase p-3 text-center">
                    politics
                  </h4>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 box">
            <div class="card border-0">
              <div class="card-body">
                <img src="@/assets/img/tech1.png" alt="">
                <div class="tech">
                  <h4 class="text-uppercase p-3 text-center">
                    technology
                  </h4>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <hr>
    </div>
    <PopularTopics />
    <BaseFooter />
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.card h4 {
    margin-bottom: 0 !important;
}
img{
    width: 100%;
    height: auto
}
.education, .kiddies, .foreign {
    background: #FFEEED;
    color: #EE6A5F;
}
.fashion, .entertainment, .politics{
    background: #FFFCED;
    color: #B49503;
}
.sport, .food, .tech{
    background: #DDFCFF;
    color: #087781;
}
hr {
    border: 0.5px solid #6A6A6A;
    margin: 50px 150px !important;
}
</style>
