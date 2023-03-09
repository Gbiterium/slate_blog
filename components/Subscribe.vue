<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <section class="newsletter d-flex justify-content-center pb-lg-5">
    <div class="subscribe d-flex align-items-center justify-content-center text-center mb-5">
      <div>
        <h4 class="text-white">
          Subscibe to Our Newsletter
        </h4>
        <p class="text-lighter">
          Get weekly update about our product on your email, no spam guaranteed we promise ✌️
        </p>
      </div>
      <div class="card border-0 shadow">
        <div class="card-body">
          <div class="d-flex justify-content-center align-items-center p-lg-4">
            <div class="envelope-icon mr-lg-3 px-lg-3 py-lg-2">
              <b-icon-envelope-fill />
            </div>
            <input type="text" class="form-control border-0 mr-3" placeholder="youremail123@gmail.com">
            <button type="submit" class="btn bg-pink text-white p-lg-3 px-lg-2">
              SUBSCRIBE
            </button>
          </div>
        </div>
      </div>
      <div class="dots-abs">
        <img src="@/assets/img/ornament.png">
      </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>

</style>
