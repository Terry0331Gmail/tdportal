<!-- 顯示單筆資料的 form，只能 readonly -->
<template>
  <div>
    <carousel :per-page="1" :autoplay="ture" :navigationEnabled="ture">
      <slide v-for="(item, index) in carouselItems" :key="index">
        <div class="card">
          <img :src="item.image" alt="">
        </div>
      </slide>    
    </carousel>
  </div>
</template>

<script>
   import { Carousel, Slide } from 'vue-carousel';
  export default {
    components: {
      Carousel,
      Slide
    },
    data() {
    },
    props: {
      carouselItems: Array,
    }

  }
</script>
