<template>
  <div class="home">
    <HeaderStore />
    <HeroStore />
    <PlantStore/>
    <InstaStore/>
    <PartnerStore/>
    <FooterStore/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderStore from "@/components/HeaderStore.vue";
import HeroStore from "@/components/HeroStore.vue";
import PlantStore from "@/components/PlantStore.vue";
import InstaStore from "@/components/InstaStore.vue";
import PartnerStore from "@/components/PartnerStore.vue";
import FooterStore from "@/components/FooterStore.vue";

export default {
  name: "Home",
  components: {
    HeaderStore,
    HeroStore,
    PlantStore,
    InstaStore,
    PartnerStore,
    FooterStore,
  },
};
</script>
