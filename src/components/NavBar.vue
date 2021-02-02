<template>
    <div class="navbar">
        <header class="text-gray-600 body-font mb-20">
            <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
            <!-- <nav class="flex lg:w-2/5 flex-wrap items-center text-base md:ml-auto">
                <a class="mr-5 hover:text-gray-900">First Link</a>
                <a class="mr-5 hover:text-gray-900">Second Link</a>
                <a class="mr-5 hover:text-gray-900">Third Link</a>
                <a class="hover:text-gray-900">Fourth Link</a>
            </nav> -->
            <router-link to="/">
            <a class="flex order-first lg:order-none lg:w-full title-font font-medium items-center text-gray-900 lg:items-center lg:justify-center ml-16 mb-4 md:mb-0">
                <img :src="logo" alt="GASK logo" width="260">
            </a></router-link>
            <div class="lg:w-2/5 inline-flex lg:justify-end ml-5 lg:ml-64">
                <button class="inline-flex items-center bg-green-500 border-0 py-3 px-8 focus:outline-none hover:bg-green-600 rounded text-base text-white mt-4 md:mt-0 shadow-md hover:shadow-lg">
                Gift A Kit Now
                </button>
            </div>
            </div>
        </header>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'NavBar',
  props: {},
  data () {
    return {
      logo: require('../assets/images/GASK_logo.png')
    }
  }
})
</script>
