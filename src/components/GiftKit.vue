<template>
    <section class="py-20 text-left">
    <div class="container px-4 mx-auto">
      <div class="flex flex-wrap -mx-8">
        <div class="w-full lg:w-1/2 px-8">
          <div class="mb-12 lg:mb-0 pb-12 lg:pb-0 border-b lg:border-b-0">
            <h2 class="mb-4 text-4xl lg:text-5xl font-bold font-heading">Help School Kids Achieve Their Dreams</h2>
            <p class="mb-8 leading-10 text-blueGray-400">
                Crypto has had a huge influence in my life. There is a huge chance it has changed yours too. <br>
                There are over <span class="font-bold" >200 million out of school children globally</span>. Sadly, those in school lack appropriate learning materials to truly achieve their goals. <br>
                Over the past couple of years, I've participated in efforts to donate proper school kits to needy school kids in sub-Saharan Africa but there's still so much to be done. <br>
                With Gift A School Kit, <b>we can help make a difference</b> . Help these kids fulfil their right to education. Help them achieve their dreams. Gift A School Kit Today.
            </p>
            <div class="flex cursor-pointer" >
                <button class="bg-green-500 text-white active:bg-green-600 font-bold uppercase text-base px-20 py-4 rounded shadow-md hover:shadow-lg outline-none focus:outline-none mr-1 mb-1" type="button" style="transition: all .15s ease">
                    Gift A Kit Now
                </button>
                <p class="underline pt-4 pl-4 hover:text-green-600">One Time</p>
                <p class="underline pt-4 pl-4 hover:text-green-600">Monthly</p>
            </div>
        </div>
        </div>
        <div class="w-full lg:w-1/2 px-8 pl-16 ">
          <ul class="space-y-12">
            <li class="flex -mx-4">
              <div class="px-4">
                <span class="flex w-16 h-16 mx-auto items-center justify-center text-2xl font-bold font-heading rounded-full bg-green-500 text-white">$5</span>
              </div>
              <div class="">
                <h3 class="text-xl font-semibold">Essentials</h3>
                <p class="text-blueGray-400 leading-loose">1 unit buys a basic school kit for a kid. This kit includes a pair of pen(cil)s, erasers, ruler, crayons and a pencil sharpener etc.</p>
                <div class="flex justify-start mt-3">
                    <button v-on:click="counter1 -= 1"><svg class="fill-current text-gray-600 w-3" viewBox="0 0 448 512"><path d="M416 208H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h384c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z" /></svg></button>
                    <input class="mx-2 border text-center w-10" type="text" v-model="counter1" />
                    <button v-on:click="counter1 += 1"><svg class="fill-current text-gray-600 w-3" viewBox="0 0 448 512"><path d="M416 208H272V64c0-17.67-14.33-32-32-32h-32c-17.67 0-32 14.33-32 32v144H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h144v144c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32V304h144c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z" /></svg></button>
                    <button class="ml-6 -mt-0 inline-flex items-center bg-green-500 border-0 py-2 px-3 focus:outline-none hover:bg-green-600 rounded text-base text-white mt-4 md:mt-0">Gift A Kit Now</button>
                </div>
            </div>
            </li>
            <li class="flex -mx-4">
              <div class="px-4">
                <span class="flex w-16 h-16 mx-auto items-center justify-center text-2xl font-bold font-heading rounded-full bg-green-500 text-white">$15</span>
              </div>
              <div class="">
                <h3 class="text-xl font-semibold">Essentials+</h3>
                <p class="text-blueGray-400 leading-loose">1 unit includes a basic school kit plus a mathematical set, a set of notebooks etc.</p>
                <div class="flex justify-start mt-3">
                    <button v-on:click="counter2 -= 1"><svg class="fill-current text-gray-600 w-3" viewBox="0 0 448 512"><path d="M416 208H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h384c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z" /></svg></button>
                    <input class="mx-2 border text-center w-10" type="text" v-model="counter2" />
                    <button v-on:click="counter2 += 1"><svg class="fill-current text-gray-600 w-3" viewBox="0 0 448 512"><path d="M416 208H272V64c0-17.67-14.33-32-32-32h-32c-17.67 0-32 14.33-32 32v144H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h144v144c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32V304h144c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z" /></svg></button>
                    <button class="ml-6 -mt-0 inline-flex items-center bg-green-500 border-0 py-2 px-3 focus:outline-none hover:bg-green-600 rounded text-base text-white mt-4 md:mt-0">Gift A Kit Now</button>
                </div>
              </div>
            </li>
            <li class="flex -mx-4">
              <div class="px-4">
                <span class="flex w-16 h-16 mx-auto items-center justify-center text-2xl font-bold font-heading rounded-full bg-green-500 text-white">$25</span>
              </div>
              <div class="">
                <h3 class="text-xl font-semibold">Essentials++</h3>
                <p class="text-blueGray-400 leading-loose">1 unit includes the above plus a school backpack, plastic folders, jotters etc. </p>
                <div class="flex justify-start mt-3">
                    <button v-on:click="counter3 -= 1"><svg class="fill-current text-gray-600 w-3" viewBox="0 0 448 512"><path d="M416 208H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h384c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z" /></svg></button>
                    <input class="mx-2 border text-center w-10" type="text" v-model="counter3" />
                    <button v-on:click="counter3 += 1"><svg class="fill-current text-gray-600 w-3" viewBox="0 0 448 512"><path d="M416 208H272V64c0-17.67-14.33-32-32-32h-32c-17.67 0-32 14.33-32 32v144H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h144v144c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32V304h144c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z" /></svg></button>
                    <button class="ml-6 -mt-0 inline-flex items-center bg-green-500 border-0 py-2 px-3 focus:outline-none hover:bg-green-600 rounded text-base text-white mt-4 md:mt-0">Gift A Kit Now</button>
                </div>
            </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'GiftKit',
  props: {},
  data () {
    return {
      counter1: 1,
      counter2: 1,
      counter3: 1
    }
  }
})
</script>
