<template>
    <div class="hero-section py-10">
        <section class="text-gray-600 body-font">
            <div class="container mx-auto flex px-5 py-24 items-center justify-center flex-col">
                <div class="text-center lg:w-2/3 w-full">
                    <h1 class="title-font lg:text-6xl text-5xl mb-6 font-medium text-gray-900 uppercase">Gift A School Kit <br> TODAY</h1>
                    <p class="mb-8 leading-relaxed font-medium ">Gift A School Kit is an indie social project working towards ensuring underpriviledged school kids get access to basic educational materials.</p>
                    <div class="flex justify-center">
                      <router-link to="/GiftKit#giftkit">
                        <button class="bg-green-500 text-white active:bg-green-600 font-bold uppercase text-base px-20 py-4 rounded shadow-md hover:shadow-lg outline-none focus:outline-none mr-1 mb-1" type="button" style="transition: all .15s ease">Gift A Kit Now
                        </button>
                      </router-link>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HeroSection',
  props: {},
  data () {
    return {
      sideImg1: require('../assets/images/Group1.png'),
      sideImg2: require('../assets/images/Group2.png')
    }
  }
})
</script>

<style lang="scss" scoped>
.hero-section {
  background-image: url('../assets/images/Group1.png'), url('../assets/images/Group2.png');
  background-position: right, left;
  background-repeat: no-repeat, no-repeat;
  background-size: 30%, auto;
}
</style>
