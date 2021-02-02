<template>
    <section class="pt-40 mx-10 text-center">
        <div class="max-w-2xl mx-auto mb-8">
        <h2 class="text-6xl leading-tight mb-6 font-semibold font-heading">Our Corporate Sponsors</h2>
        <p class="text-gray-400 leading-relaxed font-medium">Hearty thanks to these companies for supporting our cause</p>
        </div>
        <div class="flex flex-wrap mx-8">
        <div class="w-1/2 md:w-1/6 px-8 mb-8 pt-4"><img :src="corp1" alt=""></div>
        <div class="w-1/2 md:w-1/6 px-8 mb-8"><img :src="corp2" alt=""></div>
        <div class="w-1/2 md:w-1/6 text-4xl px-8 mb-8"><img src="" alt="">𝔖𝔞𝔩𝔲𝔰</div>
        <div class="w-1/2 md:w-1/6 px-8 mb-8"><img :src="corp4" alt=""></div>
        <div class="w-1/2 md:w-1/6 px-8 mb-8 pt-4"><img :src="corp5" alt=""></div>
        <div class="w-1/2 md:w-1/6 px-8 mb-8 pt-4"><img :src="corp6" alt=""></div>
        </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'CorpSponsors',
  props: {},
  data () {
    return {
      corp1: require('../assets/images/aleph.svg'),
      corp2: require('../assets/images/gitscape.svg'),
      corp4: require('../assets/images/plucky.svg'),
      corp5: require('../assets/images/facebook.svg'),
      corp6: require('../assets/images/marvel.svg')
    }
  }
})
</script>
