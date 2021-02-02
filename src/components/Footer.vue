<template>
  <footer class="text-gray-600 body-font cursor-pointer">
    <div class="container px-5 py-8 mx-auto flex items-center sm:flex-row flex-col">
      <router-link to="/">
        <a class="flex order-first lg:order-none lg:w-full title-font font-medium items-center text-gray-900 lg:items-center lg:justify-center ml-16 mb-4 md:mb-0">
                <img :src="logo" alt="GASK logo" width="260">
        </a>
      </router-link>
      <p class="text-sm text-gray-500 lg:ml-40 mr-40 sm:pl-4 sm:py-2 sm:mt-0 mt-4">© 2021 Created with love by ❤️
        <a href="https://steemit.com/@infovore" class="text-gray-600 ml-1" rel="noopener noreferrer" target="_blank">@infovore</a></p>
      <nav class="flex flex-wrap text-sm text-gray-500">
        <router-link to="/"><a class="mr-5 hover:text-gray-900">Terms of use</a></router-link>
        <router-link to="/"><a class=" hover:text-gray-900">Privacy Policy</a></router-link>
        <!-- <a class="mr-5 hover:text-gray-900">Third Link</a>
        <a class="hover:text-gray-900">Fourth Link</a> -->
      </nav>
      <span class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start"><a class="ml-3 text-gray-500"><svg fill="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24"><path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"></path></svg></a></span>
    </div>
  </footer>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Footer',
  props: {},
  data () {
    return {
      logo: require('../assets/images/GASK_logo.png')
    }
  }
})
</script>
