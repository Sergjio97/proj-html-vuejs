<template>
  <header>

    <div class="contatti">

      <div class="col-sn">
        <i class="fas fa-phone"></i>
        <span>Call us for a Free Quote: 1.800.555.6789</span>
      </div>

      <div class="col-dx">
        <i class="fab fa-facebook-f"></i>
        <i class="fab fa-twitter"></i>
        <i class="fab fa-instagram"></i>
        <i class="fab fa-youtube"></i>
      </div>

    </div>

    <Jumbo/>

  </header>
</template>

<script>
import Jumbo from '../sections/Jumbo.vue'
export default {
    name: 'Header',
    components: {
      Jumbo,
    }

}
</script>

<style lang='scss' scoped>

.contatti {
  display: flex;
  justify-content: space-around;
  background-color: #69bf14;
  color: #fff;
  padding: 10px;
}

.col-sn {
  span {
    margin-left: 10px;
  }
}

.col-dx {
  svg {
    margin-right: 10px;
  }
}

</style>