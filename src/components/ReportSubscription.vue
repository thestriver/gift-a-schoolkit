<template>
    <section class="py-20 mx-20 mt-24 mb-20">
    <div class="container px-4 mx-auto">
      <div class="flex flex-wrap justify-center items-center -mx-3">
        <div class="w-full lg:w-1/2 mb-8 text-center lg:text-left">
          <h2 class="text-3xl mb-4 lg:text-4xl font-bold font-heading">
            <span>Our Monthly</span>
            <span class="text-green-600">Progress</span>
            <span>Report</span>
          </h2>
          <p class="text-blueGray-400">Every month we release our transparency report complete with our activities and how your sponsored kits are disbursed.
        </p>
        </div>
        <div class="w-full lg:w-1/2 px-3">
          <div class="flex flex-wrap max-w-lg mx-auto">
            <div class="flex w-full md:w-2/3 px-3 mb-3 md:mb-0 md:mr-6 bg-blueGray-100 rounded border">
              <input class="w-full pl-3 py-4 text-md text-blueGray-400 font-semibold leading-none bg-blueGray-100 outline-none" v-model="emailAddress" type="text" placeholder="E-mail address">
            </div>
            <button class="w-full md:w-auto py-4 px-8 text-md text-white font-semibold leading-none bg-green-500 hover:bg-green-600 rounded" type="submit">Subscribe</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'ReportSubscription',
  props: {},
  data () {
    return {
      emailAddress: ''
    }
  }
})
</script>
