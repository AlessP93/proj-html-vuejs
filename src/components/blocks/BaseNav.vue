<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col">
                <div class="logo_header">
                    <img src="../../assets/img/avada-bakery-logo-retina-200x97.png" alt="">
                </div>
                <div class="nav_header">
                    <ul>
                        <li><a href="#">HOME</a></li>
                        <li><a href="#">SHOP</a></li>
                        <li><a href="#">ABOUT</a></li>
                        <li><a href="#">GALLERY</a></li> 
                        <li><a href="#">LOCATIONS</a></li>
                        <li><a href="#">JOURNALS</a></li> 
                        <li><a href="#">CONTANCT</a></li>
                        <li><a href="#">MY ACCOUNT</a></li>
                        <i class="fa-solid fa-cart-shopping"></i>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BaseNav',
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
        display: flex;
        justify-content: space-between;
        margin: 0 .625rem;
    }
    .logo_header img {
        width: 100px;
    }
}
.nav_header {
    align-self: end;
}
.nav_header ul {
    display: flex;
    
    li {
        margin-right: 1.25rem;
        list-style: none;
        font-size: .8125rem;

        a {
            text-decoration: none;
            color: var(--text-color-violet);
        }

        a:hover {
            border-bottom: .125rem solid var(--text-color-violet);
        }
    }
}
</style>