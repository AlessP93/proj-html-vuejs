<template>
    <footer>
        <div class="container">
            <div class="row d-flex justify-content-between">
                <div class="col-6">
                    <div class="logo_footer">
                        <img src="../../assets/img/avada-bakery-logo-retina-200x97.png" alt="">
                    </div>
                </div>
                <div class="col-6 text-end">
                    <h5>Subscribe to our Newsletter</h5>
                </div>
            </div>
        </div>
        <div class="container py-3">
            <div class="row">
                <div class="col-6">
                    <div class="nav_footer">
                        <ul class="d-flex">
                            <li v-for="(link,index) in links" :key="index"><a :href="link.url"></a>{{link.text}}</li>
                            <i class="shop fa-solid fa-cart-shopping"></i>
                            <span class="shop_number">0</span>
                        </ul>
                    </div>
                </div>
                <div class="col-6 text-end">
                    <input type="text" placeholder="Enter email adress*">
                    <button class="secondary_btn" type="submit">Subscribe</button>
                </div>
            </div>
        </div>
        <div class="container py-4">
            <div class="row d-flex">
                <div class="col-6 justify-content-between">
                    <div class="text_ft">
                        <small>© Copyright 2012 - 2020 | Avada Theme by ThemeFusion | All Right Reserved | Powered by WordPress</small>
                    </div>
                </div>
                <div class="col-6 text-end">
                    <div class="social">
                        <a href="#"><i class="fa-brands fa-instagram"></i></a>
                        <a href="#"><i class="fa-brands fa-twitter"></i></a>
                        <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                        <a href="#"><i class="fa-brands fa-pinterest-p"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'BaseFooter',
    data() {
        return {
            links: [
                {
                    text: "SHOP",
                    url: "#",
                },
                {
                    text: "ABOUT",
                    url: "#",
                },
                {
                    text: "GALLERY",
                    url: "#",
                },
                {
                    text: "LOCATIONS",
                    url: "#",
                },
                {
                    text: "JOURNALS",
                    url: "#",
                },
                {
                    text: "CONTANCT",
                    url: "#",
                },
                {
                    text: "ORDER",
                    url: "#",
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/buttons/buttons.scss';

h5 {
    color: var(--text-color-violet);
}
.logo_footer img {
    width: 15%;
}
.shop_number {
    background-color: var(--lightgrey-color);
    color: var(--text-color-violet);
    border-radius: 50%;
    margin-left: .625rem;
    padding: 0 8px;
}
.shop {
    color: var(--text-color-violet);
    align-self: center;
    }
.nav_footer {
        ul {
            padding: 0;
        }
         li {
            text-decoration: none;
            color: var(--text-color-violet);
            margin-right: 1.5625rem;
            list-style: none;
            font-size: .8125rem;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            border-bottom: .125rem solid transparent;
        }

        li:hover {
            border-bottom: .125rem solid var(--text-color-violet);
        }
}

input {
    border-radius: .3125rem;
    padding: .625rem 1.25rem;
    border: .0625rem solid var(--lightgrey-color);
    font-size: .875rem;
    margin-right: .625rem;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.social * {
    margin-left: 1.875rem;
    color: var(--text-color-violet);
    cursor: pointer;
    transition: transform 2s;
}
.social *:hover {
    transform: scale(2.2);
}

.text_ft small {
    color: var(--text-color-grey);
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.secondary_btn {
    transition: transform 2s;
    box-shadow: 10px 10px 20px rgba(100, 0, 133, 0.625);
}
.secondary_btn:hover {
    transform: scale(1.1);
}
</style>