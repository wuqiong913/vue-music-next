<template>
<<<<<<< HEAD
  <div class="recommend">
    <div class="slider-wrapper">
      <div class="slider-content">
        <slider v-if="sliders.length" :sliders="sliders"></slider>
      </div>
    </div>
=======
  <div class="recommend" >
    recommend
>>>>>>> master
  </div>
</template>

<script>
<<<<<<< HEAD
import { getRecommend } from '@/service/recommend'
import Slider from '@/components/base/slider/slider'
  export default {
    name: 'recommend',
    components: {
      Slider
    },
    data() {
      return {
        sliders: []
      }
    },
    async created() {
      const result = await getRecommend()
      console.log(result)
      this.sliders = result.sliders
=======
  
  export default {
    name: 'recommend',
    components: {
     
    },
    data() {
      return {
       
      }
    },
    computed: {
      
    },
    async created() {
      
    },
    methods: {
     
>>>>>>> master
    }
  }
</script>

<style lang="scss" scoped>
<<<<<<< HEAD
.recommend {
    position: fixed;
    width: 100%;
    top: 88px;
    bottom: 0;
    overflow: scroll;
    .slider-wrapper {
      position: relative;
      width: 100%;
      height: 0;
      padding-top: 40%;
      overflow: hidden;
      .slider-content {
        position: absolute;
        left: 0;
        top: 0;
        width: 100%;
        height: 100%;
      }
    }
}
=======

>>>>>>> master
</style>
