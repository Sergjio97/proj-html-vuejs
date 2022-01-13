<template>
  <div class="box">
      <ul v-for="(avada, index) in avadaList" :key="index">
          <li><h2>{{avada.title}}</h2></li>
          <li><a href="#">{{avada.link}}</a></li>
      </ul>
  </div>
</template>

<script>
export default {
    name: 'FooterNavSn',
    props: {
        avadaList: Array
    }
}
</script>

<style lang='scss' scoped>
.box {
    margin-right: 160px;
    ul {
        list-style: none;
    }
    a {
        text-decoration: none;
        color: black;
    }
    h2 {
        text-transform: uppercase;
        margin-bottom: 40px;
    }
}

</style>