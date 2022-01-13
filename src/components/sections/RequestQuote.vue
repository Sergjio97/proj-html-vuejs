<template>
  <section class="request-quote">
      <div class="box">
        <h1>Request A Free Quote</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
        <a href="#"><strong>click here</strong></a>
      </div>
  </section>
</template>

<script>
export default {
    name: 'RequestQuote'
}
</script>

<style lang='scss' scoped>
.request-quote {
    text-align: center;
    padding: 200px 0px;
    background-image: url(../../assets/img/avada-movers-request-quote-background.jpg);
    border-bottom: 15px solid #69bf14;
    .box {
        width: 35%;
        margin: 0 auto;
    }
    h1 {
        font-size: 59px;
        margin-bottom: 30px;
        color: #69bf14;
    }
    p {
        line-height: 2.0;
        margin-bottom: 45px;
    }
    a {
        text-decoration: none;
        color: #fff;
        text-transform: uppercase;
        background-color: #1975c0;
        padding: 10px 20px;
        border-radius: 25px;
    }
    a:hover {
        filter: opacity(80%);
    }
}
</style>