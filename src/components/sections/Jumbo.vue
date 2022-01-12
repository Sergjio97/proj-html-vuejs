<template>
  <div class="jumbo">

    <nav>
      <img src="../../assets/img/avada-movers-logo.png" alt="logo header">
      <ul>
        <li v-for="(link, index) in links" :key="index">
          <a :href="link.link">{{link.title}}</a>
        </li>
      </ul>
    </nav>

    <div class="title">
      <h3>without the hassle</h3>
      <h1>We make it simple</h1>
      <h3>service with quality and customer satisfaction</h3>
    </div>

  </div>
</template>

<script>
export default {
    name: 'Jumbo',
    props: {
      links: Array
    }
}
</script>

<style lang='scss' scoped>

.jumbo {
  background-image: url(../../assets/img/avada-movers-homeherobackground-final.jpg);
  background-position: center top;
  nav {
    width: 100%;
    padding-top: 1%;
    display: flex;
    justify-content:space-evenly;
    align-items: center;
    img {
      cursor: pointer;
    }
    li {
      display: inline;
      cursor: pointer;
      margin-right: 35px;
      a {
        text-decoration: none;
        color: black;
        font-weight: bolder;
      }
      a:hover {
        color: #69bf14;
      }
    }
    li:first-child {
      a {
        color: #69bf14;
      }
    }
    li:last-child {
      background-color: #1975c0;
      text-transform: uppercase;
      padding: 15px 30px;
      border-radius: 25px;
      a {
        color: #fff;
      }
    }
    li:last-child:hover {
      filter:opacity(80%);
    }
  }
  .title {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding-top: 10%;
    padding-bottom: 14%;
    h1 {
      font-size: 64px;
      text-transform: uppercase;
      margin-top: 20px;
      margin-bottom: 20px;
    }
    h3 {
      font-size: 16px;
      text-transform: uppercase;
      color: #6b6b6b;
    }
  }
}
</style>