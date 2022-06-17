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
                    <h6>Subscribe to our Newsletter</h6>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <ul>
                        <li><a href="#">SHOP</a></li>
                        <li><a href="#">ABOUT</a></li>
                        <li><a href="#">GALLERY</a></li>
                        <li><a href="#">LOCATIONS</a></li> 
                        <li><a href="#">JOURNALS</a></li>
                        <li><a href="#">CONTANCT</a></li> 
                        <li><a href="#">ORDER</a></li>
                        <i class="fa-solid fa-cart-shopping"></i>
                        <span class="shop_footer">0</span>
                    </ul>
                </div>
                <div class="col-6"></div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'BaseFooter'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/buttons/buttons.scss';

.logo_footer img {
    width: 15%;
}

.shop_footer {
    background-color: var(--lightgrey-color);
    color: var(--text-color-violet);
}

</style>