<template>
    <section>
        <div class="service-card">
            <img src="../../assets/img/avada-movers-serviceonephoto-final-400x255.jpg" alt="Two Man Teams">
            <h2>Two Man Teams</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
            <a href="#"><strong>read more</strong></a>
        </div>

        <div class="service-card">
            <img src="../../assets/img/avada-movers-servicetwophoto-final-400x255.jpg" alt="We Do All The Lifting">
            <h2>We Do All The Lifting</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
            <a href="#"><strong>read more</strong></a>
        </div>

        <div class="service-card">
            <img src="../../assets/img/avada-movers-servicethreephoto-final-400x255.jpg" alt="Coast To Coast">
            <h2>Coast To Coast</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam ac consectetur augue. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
            <a href="#"><strong>read more</strong></a>
        </div>
    </section>   
</template>

<script>
export default {
    name: 'ServiceCard',
    props: {
        ServiceCard: Array
    },
}
</script>

<style lang='scss' scoped>
section {
    width: 50%;
    display: flex;
    justify-content: space-between;
}
.service-card {
    width: 30%;
    padding-bottom: 40px;
    text-align: center;
    img {
        width: 100%;
        border-bottom: 20px solid #e9e9e9;
    }
    border: 20px solid #e9e9e9;
    h2 {
        color: #1975c0;
        margin-top: 30px;
        margin-bottom: 30px;
    }
    p {
        color: #6b6b6b;
        margin-bottom: 50px;
        line-height: 2.0;
    }
    a {
        text-decoration: none;
        color: #fff;
        background-color: #1975c0;
        text-transform: uppercase;
        padding: 10px 25px;
        border-radius: 20px;
    }
    a:hover {
        filter:opacity(80%);
    }
}
</style>