<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div class="row posts my-5">
    <div v-for="topic in topics" :key="topic" class="col-md-3">
      <div class="card border-0 shadow scroll-active">
        <div class="card-body">
          <img src="@/assets/img/cactus.png" alt="">
          <div class="p-3">
            <h5>{{ topic.topic }}</h5>
            <p class="text-blue">
              Thur, January 12, 2023 - 9:15 am
            </p>
            <p class="text-light">
              Lorem ipsum dolor sit amet consectetur. Facilisi gravida sed enim tincidunt pellentesque mi amet. At risus nunc ac at pretium rhoncus duis. Pulvinar massa vitae vel sit commodo eget purus. Congue aliquam tellus arcu varius mauris tristique tellus pellentesque. Id nibh nisi duis maecenas eu lacus leo pulvinar. Tincidunt dictum tristique fermentum ornare. Pharetra eu enim placerat ante mauris ac pellentesque. Aliquet enim mollis egestas blandit. In tincidunt risus lacinia viverra in sagittis. Sagittis neque consectetur sed vel enim. Sem eu porttitor urna pharetra arcu adipiscing. Nunc vitae in odio elit egestas mi lobortis. Leo tristique dignissim adipiscing dui non pellentesque. Nisi ac porttitor egestas sit risus.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      topics: [
        { topic: 'The Beginning of a new dawn as Peter Obi wins the Presidential election.' },
        { topic: 'The Beginning of a new dawn as Peter Obi wins the Presidential election.' },
        { topic: 'The Beginning of a new dawn as Peter Obi wins the Presidential election.' },
        { topic: 'The Beginning of a new dawn as Peter Obi wins the Presidential election.' }
      ]
    }
  }
}
</script>

<style scoped>
.posts img {
  width: 100%;
  height: auto;
}
</style>
