<template>
  <main>
    <Testimonials/>
    <Service/>
    <FreeQuote/>
    <Customers/>
    <RequestQuote/>
  </main>
</template>

<script>
import Testimonials from '../sections/Testimonials.vue';
import Service from '../sections/Service.vue';
import FreeQuote from '../sections/FreeQuote.vue';
import Customers from '../sections/Customers.vue';
import RequestQuote from '../sections/RequestQuote.vue'
export default {
    name: 'Main',
    components: {
      Testimonials,
      Service,
      FreeQuote,
      Customers,
      RequestQuote
    }
}
</script>

<style lang='scss' scoped>
main {
  width: 100%;
}

</style>