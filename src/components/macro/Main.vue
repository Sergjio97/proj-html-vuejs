<template>
  <main>
    <Testimonials/>
    <Service/>
  </main>
</template>

<script>
import Testimonials from '../sections/Testimonials.vue';
import Service from '../sections/Service.vue';
export default {
    name: 'Main',
    components: {
      Testimonials,
      Service,
    }
}
</script>

<style lang='scss' scoped>
main {
  width: 100%;
}

</style>