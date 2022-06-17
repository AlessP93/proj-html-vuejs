<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-5">
                <div class="logo_header">
                    <img src="../../assets/img/avada-bakery-logo-retina-200x97.png" alt="">
                </div>
            </div>
            <div class="col-7 align-self-end">
                <div class="nav_header">
                    <ul class="d-flex justify-content-end">
                        <li v-for="(link,index) in links" :key="index"><a :href="link.url"></a>{{link.text}}</li>
                        <i class="shop fa-solid fa-cart-shopping"></i>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BaseNav',
    data() {
        return {
            links: [
                {
                    text: "HOME",
                    url: "#",
                },
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
                    text: "MY ACCOUNT",
                    url: "#",
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.container-fluid {
    position: fixed;
    z-index: 10;
    left: 0;
    top: 0;
    background-color: #f3e7f1;
    box-shadow: 0px 30px 20px #f3e7f1;
    padding: .625rem;
    opacity: 0.9;
    
    .col {
        margin: 0 .625rem;
    }
    .logo_header img {
        width: 100px;
    }
}
.nav_header {
    align-self: end;

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
.shop {
    color: var(--text-color-violet);
    align-self: center;
}
</style>