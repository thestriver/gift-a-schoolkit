<template>
  <div class="home">
    <NavBar />
    <HeroSection />
    <GiftKit />
    <Progress />
    <CorpSponsors />
    <ReportSubscription />
    <Footer />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
// import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src
import NavBar from '@/components/NavBar.vue'
import HeroSection from '@/components/HeroSection.vue'
import GiftKit from '@/components/GiftKit.vue'
import Progress from '@/components/Progress.vue'
import CorpSponsors from '@/components/CorpSponsors.vue'
import ReportSubscription from '@/components/ReportSubscription.vue'
import Footer from '@/components/Footer.vue'

export default defineComponent({
  name: 'Home',
  components: {
    NavBar,
    HeroSection,
    GiftKit,
    Progress,
    CorpSponsors,
    ReportSubscription,
    Footer
  }
})
</script>
