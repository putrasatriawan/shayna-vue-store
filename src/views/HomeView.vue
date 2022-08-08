<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBannerShayna />
    <InstaShayna />
    <PathnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import WomenBannerShayna from "@/components/WomenBannerShayna.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PathnerShayna from "@/components/PathnerShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "HomeView",
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBannerShayna,
    InstaShayna,
    PathnerShayna,
    FooterShayna,
  },
};
</script>
