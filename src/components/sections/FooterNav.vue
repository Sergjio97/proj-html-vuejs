<template>
  <section class="footer-nav">
    <nav>
        <ul>
            <li><h2>About</h2></li>
            <li><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis convallis ex ut sem accumsan vehicula. Integer elit arcu, hendrerit id sapien ut, facilisis accumsan arcu.</p></li>
            <li><img src="../../assets/img/avada-movers-logo.png" alt="logo header"></li>
        </ul>
        <FooterNavSn :avadaList="avadaList"/>
        <FooterNavDx :postList="postList"/>
    </nav>
    <div class="contact">
        <p>© Copyright 2012 - 2022 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress</p>
        <div class="box">
            <i class="fab fa-facebook-f"></i>
            <i class="fab fa-twitter"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-youtube"></i>
        </div>
    </div>
  </section>
</template>

<script>
import FooterNavSn from '../elements/FooterNavSn.vue';
import FooterNavDx from '../elements/FooterNavDx.vue'
export default {
    name: 'FooterNav',
    components : {
        FooterNavSn,
        FooterNavDx
    },
    data() {
        return {
            avadaList: [
                {
                    title: 'Avada movers'
                },
                {
                    link: 'Home'
                },
                {
                    link: 'Rates'
                },
                {
                    link: 'Testimonials'
                },
                {
                    link: 'Blog'
                },
                {
                    link: 'Free Quote'
                }
            ],

            postList: [
                {
                    title: 'recent posts'
                },
                {
                    link: 'Heading Out To College?'
                },
                {
                    link: 'Moving Your Business?'
                },
                {
                    link: 'Outstanding Quality'
                },
                {
                    link: 'Cost of Moving'
                },
                {
                    link: 'Best Moving Tips'
                }
            ],
        }
    }
}
</script>

<style lang='scss' scoped>
.footer-nav {
    width: 100%;
    ul {
        width: 35%;
        margin-right: 160px;
        list-style: none;
    }
    nav {
        display: flex;
        width: 50%;
        margin: 0 auto;
        padding: 80px 0px;
    }
    h2 {
        text-transform: uppercase;
        margin-bottom: 40px;
    }
    p {
        margin-bottom: 40px;
        color: #6b6b6b;
        line-height: 2.0;
    }

    .contact {
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        background-color: #69bf14;
        text-align: center;
        color: #fff;
        padding: 30px 0px;
        p {
            color: #fff;
        }
        svg {
            cursor: pointer;
            margin-right: 20px;
            font-size: 22px;
        }
        svg:hover {
            color: #6b6b6b;
        }
    }
}
</style>