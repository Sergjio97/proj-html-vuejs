<template>
  <main>

    <section class="testimonials">
      <div>
        <h3>Headache free</h3>
        <h1>Award Winning Moving Company</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac augue. Orci varius natoque penatibus et magnis dis parturient montes, ridiculus mus. Aliquam enim leo, condimentum facilisis nulla sed, cursus arcu. Aliquam enim leo.</p>
        <a href="#"><strong>Read our testimonials</strong></a>
      </div>
    </section>

  </main>
</template>

<script>
export default {
    name: 'Main'
}
</script>

<style lang='scss' scoped>
main {
  width: 100%;
}
.testimonials {
  width: 100%;
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  background-color: #e9e9e9;
  padding: 100px 0px;
  div {
    width: 25%;
    text-align: center;
    padding: 60px 0px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  h3 {
  color: #afaeae;
  text-transform: uppercase;
  margin-bottom: 15px;
  }
  h1 {
    font-size: 59px;
    color: #69bf14;
    margin-bottom: 15px;
  }
  p {
    line-height: 2.0;
    font-size: 14px;
    color: #6b6b6b;
    margin-bottom: 15px;
  }
  a {
    width: 45%;
    text-decoration: none;
    text-transform: uppercase;
    padding: 10px;
    border-radius: 20px;
    background-color: #1975c0;
    color: #fff;
    display: block;
  }
  a:hover {
    filter:opacity(80%);
  }
}
</style>