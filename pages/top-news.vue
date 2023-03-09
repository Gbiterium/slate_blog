<template>
  <div>
    <BaseHeader />
    <div class="top-news">
      <div class="top-news-header d-lg-flex my-4">
        <div class="mr-4">
          <b-icon-arrow-left-short />
          <span>Back</span>
        </div>
        <div class="d-flex fs-10">
          <span class="mr-3">Home</span>
          <b-icon-chevron-right class="fs-16 mr-3" />
          <span class="mr-3">Top News</span>
          <b-icon-chevron-right class="fs-16 mr-3" />
          <span class="text-blue text-decoration-underline">Digital learning and its incorporation into early education.</span>
        </div>
      </div>
      <div class="top-news-content mb-5">
        <img src="@/assets/img/teach.png" alt="">
        <h4 class="font-weight-bold text-capitalize py-4">
          Digital learning and its incorporation into early education.
        </h4>
        <p class="text-light">
          Lorem ipsum dolor sit amet consectetur. Erat nisl semper aenean duis
          purus et id sem. Malesuada quam porta feugiat ultrices id cras
          imperdiet. Viverra donec malesuada nec pellentesque. Iaculis urna mus
          semper scelerisque. Porta venenatis lacinia commodo leo non laoreet.
          Suspendisse vitae in nulla lobortis gravida adipiscing. Lorem ipsum
          dolor sit amet consectetur. Erat nisl semper aenean duis purus et id
          sem. Malesuada quam porta feugiat ultrices id cras imperdiet. Viverra
          donec malesuada nec pellentesque. Iaculis urna mus semper scelerisque.
          Porta venenatis lacinia commodo leo non laoreet. Suspendisse vitae in
          nulla lobortis gravida adipiscing.Lorem ipsum dolor sit amet
          consectetur. Erat nisl semper aenean duis purus et id sem. Malesuada
          quam porta feugiat ultrices id cras imperdiet. Viverra donec malesuada
          nec pellentesque. Iaculis urna mus semper scelerisque. Porta venenatis
          lacinia commodo leo non laoreet. Suspendisse vitae in nulla lobortis
          gravida adipiscing. Lorem ipsum dolor sit amet consectetur. Erat nisl
          semper aenean duis purus et id sem. Malesuada quam porta feugiat
          ultrices id cras imperdiet. Viverra donec malesuada nec pellentesque.
          Iaculis urna mus semper scelerisque. Porta venenatis lacinia commodo
          leo non laoreet. Suspendisse vitae in nulla lobortis gravida
          adipiscing.
        </p>
        <div class="d-flex justify-content-between">
          <h5 class="font-weiight-bold">
            By MacAnthony Alex KAchie
          </h5>
          <p class="text-blue">
            Thur, January 12, 2023 - 9:15 am
          </p>
        </div>
      </div>
    </div>
    <hr>
    <PopularTopics />
    <BaseFooter />
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
img {
  width: 100%;
  height: auto;
}
h4 {
    font-size: 4vw;
}
hr {
    border: 0.5px solid #6A6A6A;
    margin: 50px 150px !important;
}
</style>
