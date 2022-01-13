<template>
    <section class="customers">
        <h4>Happy customers</h4>
        <h1>Testimonials</h1>
        <div class="card-box">
            <div class="card">
                <img src="../../assets/img/avada-movers-johndoe-final-200x200.jpg" alt="john doe">
                <h2>John Doe</h2>
                <p>“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lectus dolor, aliquet sed maximus et, vestibulum pulvinar leo. Vivamus varius pretium fermentum.”</p>
            </div>
            <div class="card">
                <img src="../../assets/img/avada-movers-janedoe-final-200x200.jpg" alt="Jane doe">
                <h2>Jane Doe</h2>
                <p>“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lectus dolor, aliquet sed maximus et, vestibulum pulvinar leo. Vivamus varius pretium fermentum.”</p>
            </div>
            <div class="card">
                <img src="../../assets/img/avada-movers-johnsmith-final-200x200.jpg" alt="john Smith">
                <h2>John Smith</h2>
                <p>“Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent lectus dolor, aliquet sed maximus et, vestibulum pulvinar leo. Vivamus varius pretium fermentum.”</p>
            </div>
        </div>
        <a href="#"><strong>Read more Testimonials</strong></a>
    </section>
</template>

<script>

export default {
    name: 'Customers',
}
</script>

<style lang='scss' scoped>
.customers {
    width: 100%;
    text-align: center;
    padding: 220px 0px;
    background-image: url(../../assets/img/avada-movers-testimonial-background.jpg);
    background-position: center;
    h4 {
        color: #afaeae;
        text-transform: uppercase;
        margin-bottom: 15px;
    }
    h1 {
        font-size: 59px;
        color: #69bf14;
    }
    h2 {
        color: #1975c0;
        margin-bottom: 30px;
    }
    a {
        text-decoration: none;
        color: #fff;
        background-color: #1975c0;
        padding: 10px 25px;
        border-radius: 20px;
        text-transform: uppercase;
    }
    a:hover {
        filter: opacity(80%);
    }
    p {
        color: #6b6b6b;
        line-height: 2.0;
    }
    .card-box {
        height: 300px;
        width: 50%;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin-bottom: 120px;
        margin-top: 80px;
        
        .card {
            width: 30%;
            text-align: center;
        }
        img {
            width:40%;
            border-radius: 50%;
            margin-bottom: 30px;
        }
    }
}
</style>