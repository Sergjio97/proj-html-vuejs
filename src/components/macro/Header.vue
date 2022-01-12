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

    <Jumbo :links="links"/>

    <h3><i class="far fa-paper-plane"></i>get a free quote online now!</h3>

  </header>
</template>

<script>
import Jumbo from '../sections/Jumbo.vue'
export default {
    name: 'Header',
    components: {
      Jumbo,
    },
    data() {
      return {
        links: [
          {
            title: 'Home',
            link: '#'
          },
          {
            title: 'Rates',
            link: '#'
          },
          {
            title: 'Testimonials',
            link: '#'
          },
          {
            title: 'FAQ',
            link: '#'
          },
          {
            title: 'Blog',
            link: '#'
          },
          {
            title: 'Contact',
            link: '#'
          },
          {
            title: 'Free quote',
            link: '#'
          }
        ]
      }
    }
}
</script>

<style lang='scss' scoped>

.contatti {
  display: flex;
  justify-content: space-around;
  background-color: #69bf14;
  color: #fff;
  padding: 15px;
  font-size: 13px;
}

.col-sn {
  span {
    margin-left: 10px;
  }
}

.col-dx {
  svg {
    margin-right: 15px;
    cursor: pointer;
    font-size: 16px;
  }
  svg:hover {
    color: #6b6b6b;
  }
}

h3 {
  display: block;
  width: 100%;
  text-transform: uppercase;
  text-align: center;
  background-color: #1975c0;
  color: #fff;
  padding: 60px 0px;
  cursor: pointer;
  svg {
    margin-right: 15px;
  }
}
h3:hover {
  filter:opacity(80%);
}

</style>