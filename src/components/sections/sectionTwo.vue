<template>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-12 text-center">
                    <small>CORPORATE & WEDDINGS</small>
                    <h2>Baking Special Moments</h2>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row py-5">
                <div class="col-6">
                    <div class="img_slot">
                        <img src="../../assets/img/corporate-bg.jpg" alt="">
                    </div>
                </div>
                <div class="col-6">
                    <div class="img_slot">
                        <img src="../../assets/img/wedding-bg.jpg" alt="">
                    </div>
                </div>
            </div> 
        </div>   
        <div class="container py-5">
            <div class="row text-center">
                <div class="col-4 align-self-center p-5">
                    <h5>Find a freschly backed product perfect for you</h5>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cumque reprehenderit voluptatum odit vitae excepturi iure quis.</p>
                    <button class="secondary_btn">Shop All Product</button>
                </div>
                <div class="col-2">
                    <img src="../../assets/img/choco-chip-cookies.jpg" alt="">
                    <div class="py-2">Choco Chip Cookies</div>
                    <small>$19.00 - $39.00</small>
                </div>
                <div class="col-2">
                    <img src="../../assets/img/strawberry-jam-cookies.jpg" alt="">
                    <div class="py-2">Strawberry Jam Cookies</div>
                    <small>$24.00 - $62.00</small>
                </div>
                <div class="col-2">
                    <img src="../../assets/img/strawberry-donut.jpg" alt="">
                    <div class="py-2">Strawberry Donut</div>
                    <small>$24.00 - $42.00</small>
                </div>
                <div class="col-2">
                    <img src="../../assets/img/perfect-macarons.jpg" alt="">
                    <div class="py-2">Perfect Macarons</div>
                    <small>$18.00 - $52.00</small>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'sectionTwo',
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/buttons/buttons.scss';
small, p {
    color: var(--text-color-grey);
}
h2, div {
    color: var(--text-color-violet);
}
h5 {
    font-weight: bold;
}

.img_slot{
       display: flex;
}
    img {
        width: 100%;
    }
</style>