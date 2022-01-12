<template>
  <main>
    <Testimonials/>
    <Service/>
    <FreeQuote/>
  </main>
</template>

<script>
import Testimonials from '../sections/Testimonials.vue';
import Service from '../sections/Service.vue';
import FreeQuote from '../sections/FreeQuote.vue';
export default {
    name: 'Main',
    components: {
      Testimonials,
      Service,
      FreeQuote,
    }
}
</script>

<style lang='scss' scoped>
main {
  width: 100%;
}

</style>