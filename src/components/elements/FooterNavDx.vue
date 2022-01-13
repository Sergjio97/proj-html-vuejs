<template>
  <div class="box">
      <ul v-for="(post, index) in postList" :key="index">
          <li><h2>{{post.title}}</h2></li>
          <li><a href="#">{{post.link}}</a></li>
      </ul>
  </div>
</template>

<script>
export default {
    name: 'FooterNavDx',
    props: {
        postList: Array
    }
}
</script>

<style lang='scss' scoped>
.box {
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