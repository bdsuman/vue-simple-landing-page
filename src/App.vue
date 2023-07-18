<script setup>

import Header from "@/components/Header.vue";
import Hero from "@/components/Hero.vue";
import Feature from "@/components/Feature.vue";
import Pricing from "@/components/Pricing.vue";
import Promo from "@/components/Promo.vue";
import Footer from "@/components/Footer.vue";
</script>

<template>
  <div class="body-wrap">
    <Header></Header>
    <main>
        <Hero></Hero>
<!--        <Feature></Feature>-->

        <Pricing></Pricing>
        <Promo></Promo>
    </main>
    <Footer></Footer>
  </div>
</template>

<style scoped>

</style>
