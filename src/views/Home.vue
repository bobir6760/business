<template>
  <div class="home">
    <Navbar />
    <Best />
    <Business />
    <Level />
    <More />
    <Logo />
    <Discover />
    <Features />
    <Address />
    <Pricing />
    <Finish />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Best from "@/components/Best.vue";
import Business from "@/components/Business.vue";
import Level from "@/components/Level.vue";
import More from "@/components/More.vue";
import Logo from "@/components/Logo.vue";
import Discover from "@/components/Discover.vue";
import Features from "@/components/Features.vue";
import Address from "@/components/Address.vue";
import Pricing from "@/components/Pricing.vue";
import Finish from "@/components/Finish.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Best,
    Business,
    Level,
    More,
    Logo,
    Discover,
    Features,
    Address,
    Pricing,
    Finish,
  },
};
</script>
