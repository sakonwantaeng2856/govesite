<template>
  <v-app>
    <Navbar />
    <Silde />
    <spot />
    <!-- <feaure /> -->
    <pricing />
    <contact />
    <footerA />
  </v-app>
</template>
<script>
import Navbar from '~/components/navbar.vue'
import Silde from '~/components/silde.vue'
import spot from '~/components/spot.vue'
import pricing from '~/components/pricing.vue'
import footerA from '~/components/footerA.vue'
import contact from '~/components/contact.vue'
// import feaure from '~/components/feaure.vue'
export default {
  components: {
    spot,
    Navbar,
    Silde,
    pricing,
    footerA,
    contact,
    // feaure,
  },
}
</script>
