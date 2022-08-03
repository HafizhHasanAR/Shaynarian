<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <BanerShayna />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from "@/components/HeaderShayna.vue";
import HeroShayna from "@/components/HeroShayna.vue";
import BanerShayna from "@/components/BanerShayna.vue";
import InstaShayna from "@/components/InstaShayna.vue";
import PartnerShayna from "@/components/PartnerShayna.vue";
import FooterShayna from "@/components/FooterShayna.vue";

export default {
  name: "HomeView",
  components: {
    HeaderShayna,
    HeroShayna,
    BanerShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna,
  },
};
</script>
