<template>
  <section class="free-quote">
      <div class="box">
          <h3>We remove the headache from moving</h3>
          <h1>Move With Ease</h1>
          <p>With our super simple service we can take you from getting a quote, right through to being in your new home with all of your belongings securely packed and safely delivered, even in the rooms of your choice.</p>
          <a href="#"><strong>get a free quote now</strong></a>
      </div>
  </section>
</template>

<script>
export default {
    name: 'FreeQuote'
}
</script>

<style lang='scss' scoped>
.free-quote {
    padding: 240px 0px;
    display: flex;
    align-items: center;
    background-image: url(../../assets/img/avada-movers-movewithease-background-new.jpg);
    background-repeat: no-repeat;
    background-position: top;
    .box {
        background-color: #69bf14;
        text-align: center;
        width: 28%;
        display: flex;
        flex-direction: column;
        align-items: center;
        border: 20px solid #4c8d53;
        padding: 50px 0px;
        margin-left: 48%;
        h1 {
            font-size: 44px;
            color: #fff;
            padding-bottom: 10px;
            border-bottom: 2px solid #8fce53 ;
            width: 50%;
        }
        h3 {
            text-transform: uppercase;
            color: #fff;
            margin-bottom: 15px;
        }
        p {
            color: #fff;
            line-height: 2.0;
            margin-top: 30px;
            margin-bottom: 30px;
        }
        a {
            padding: 10px 25px;
            border-radius: 20px;
            background-color: #1975c0;
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
        }
        a:hover {
            filter: opacity(80%);
        }
    }
}

</style>