<template>
  <div class="home">
     <HeaderMaulida/>
     <HeroSection/>
     <WomenBaner/>
     <InstaStore/>
     <LogoStore/>
     <FooterSelection/>
      <RelatedProducts/>
       </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderMaulida from '@/components/HeaderMaulida.vue'
import HeroSection from '@/components/HeroSection.vue'
import WomenBaner from '@/components/WomenBaner.vue'
import InstaStore from '@/components/InstaStore.vue'
import LogoStore from '@/components/LogoStore.vue'
import FooterSelection from '@/components/FooterSelection.vue'



export default {
  name: 'Home',
  components: {
    HeaderMaulida,
    HeroSection,
    WomenBaner,
    InstaStore,
    LogoStore,
   FooterSelection
   
  }
}
</script>
