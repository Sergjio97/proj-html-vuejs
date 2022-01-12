<template>
  <section class="service">
      <h3>We are a professional</h3>
      <h1>Full-Service Solution</h1>
      <div class="box">
        <ServiceCard/>
      </div>
  </section>
</template>

<script>
import ServiceCard from '../elements/ServiceCard.vue'
export default {
    name: 'Service',
    components: {
        ServiceCard,
    },

}
</script>

<style lang='scss' scoped>
.service {
    width: 100%;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    padding: 200px 0px;
    h3 {
        color: #afaeae;
        text-transform: uppercase;
        margin-bottom: 15px;
    }
    h1 {
        font-size: 59px;
        color: #69bf14;
        margin-bottom: 60px;
    }
    .box {
        width: 100%;
        display: flex;
        justify-content: center;
    }
}
</style>