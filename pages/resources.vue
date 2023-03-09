<template>
  <div>
    <BaseHeader />
    <div class="resources-page">
      <div class="resources-header d-flex mt-3">
        <div class="mr-4">
          <b-icon-arrow-left-short />
          <span>Back</span>
        </div>
        <span class="text-blue text-decoration-underline">Resources</span>
      </div>
      <div class="resources-content">
        <h4 class="my-4 font-weight-bold">
          Resources
        </h4>
        <div class="row mb-5">
          <div class="col-md-4 box">
            <div class="card">
              <div class="card-body">
                <img src="@/assets/img/people.png" alt="">
                <div class="p-3">
                  <h4 class="font-weight-bold fs-16">
                    The Stories of success behind remote learning
                  </h4>
                  <p class="text-light fs-16">
                    Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......
                  </p>
                  <a class="float-right text-capitalize mb-3 text-decoration-underline">Go to blog</a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 box">
            <div class="card">
              <div class="card-body">
                <img src="@/assets/img/glass.png" alt="">
                <div class="p-3">
                  <h4 class="font-weight-bold fs-16">
                    Autistic Children and books on how to train them.
                  </h4>
                  <p class="text-light fs-16">
                    Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......
                  </p>
                  <a class="float-right text-capitalize mb-3 text-decoration-underline">Go to link</a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card scroll-active">
              <div class="card-body">
                <div class="p-3 mt-2">
                  <h4 class="font-weight-bold fs-16">
                    Autistic Children and books on how to train them.
                  </h4>
                  <p class="text-light fs-16 pt-1">
                    Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor.Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......
                  </p>
                  <a class="float-right text-capitalize mb-3 text-decoration-underline">Go to link</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4 box">
            <div class="card">
              <div class="card-body">
                <img src="@/assets/img/people.png" alt="">
                <div class="p-3">
                  <h4 class="font-weight-bold fs-16">
                    Autistic Children and books on how to train them.
                  </h4>
                  <p class="text-light fs-16">
                    Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......
                  </p>
                  <a class="float-right text-capitalize mb-3 text-decoration-underline">Go to blog</a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 box">
            <div class="card">
              <div class="card-body">
                <img src="@/assets/img/glass.png" alt="">
                <div class="p-3">
                  <h4 class="font-weight-bold fs-16">
                    The Stories of success behind remote learning
                  </h4>
                  <p class="text-light fs-16">
                    Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......
                  </p>
                  <a class="float-right text-capitalize mb-3 text-decoration-underline">Go to link</a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-4 box">
            <div class="card scroll-active">
              <div class="card-body">
                <div class="p-3 mt-2">
                  <h4 class="font-weight-bold fs-16">
                    Autistic Children and books on how to train them.
                  </h4>
                  <p class="text-light fs-16 pt-1">
                    Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor.Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......Lorem ipsum dolor sit amet consectetur. Semper et ut vitae viverra vel venenatis et. Ultricies aliquet gravida est id auctor......
                  </p>
                  <a class="float-right text-capitalize mb-3 text-decoration-underline">Go to link</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <RegisterSchool />
    <hr class="m-5">
    <PopularTopics />
    <BaseFooter />
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
img {
    width: 100%;
    height: auto;
}
.card{
    border: 0.5px solid #6A6A6A;
}
hr {
    border: 0.5px solid #6A6A6A;
    margin: 50px 150px !important;
}
</style>
