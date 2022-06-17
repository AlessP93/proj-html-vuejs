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
                    <div class="img_slot_one"></div>
                </div>
                <div class="col-6">
                    <div class="img_slot_two"></div>
                </div>
            </div> 
        </div>   
        <div class="container py-5">
            <div class="row text-center">
                <div class="bakery_img d-flex justify-content-between">
                    <div class="col-3 align-self-center p-52">
                        <h2>Find a freschly backed product perfect for you</h2>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Cumque reprehenderit voluptatum odit vitae excepturi iure quis.</p>
                        <button class="secondary_btn">Shop All Product</button>
                    </div>
                    <div class="col-2">
                        <div class="arrow">
                            <img src="../../assets/img/choco-chip-cookies.jpg" alt="">
                            <span><i class="arrow_left fa-solid fa-angle-left"></i></span>
                        </div>
                        <h5 class="py-2">Choco Chip Cookies</h5>
                        <small>$19.00 - $39.00</small>
                    </div>
                    <div class="col-2">
                        <img src="../../assets/img/strawberry-jam-cookies.jpg" alt="">
                        <h5 class="py-2">Strawberry Jam Cookies</h5>
                        <small>$24.00 - $62.00</small>
                    </div>
                    <div class="col-2">
                        <img src="../../assets/img/strawberry-donut.jpg" alt="">
                        <h5 class="py-2">Strawberry Donut</h5>
                        <small>$24.00 - $42.00</small>
                    </div>
                    <div class="col-2">
                        <div class="arrow">
                            <img src="../../assets/img/perfect-macarons.jpg" alt="">
                            <span><i class="arrow_right fa-solid fa-angle-right"></i></span>
                        </div>
                        <h5 class="py-2">Perfect Macarons</h5>
                        <small>$18.00 - $52.00</small>  
                    </div>
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

small {
    color: var(--text-color-violet);
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
p {
    color: var(--text-color-grey);
}
h2, div {
    color: var(--text-color-violet);
}
.img_slot_one {
    background-image: url('../../assets/img/corporate-bg.jpg');
    background-size: cover;
    background-position: center;
    height: 500px;
    width: 100%;
 
}
.img_slot_two {
    background-image: url('../../assets/img/wedding-bg.jpg');
    background-size: cover;
    background-position: center;
    height: 500px;
    width: 100%;
 
}
.bakery_img img {
    width: 100%;
}
.secondary_btn {
    transition: transform 2s;
    box-shadow: -10px 10px 20px rgba(100, 0, 133, 0.625);
}
.secondary_btn:hover {
    transform: scale(1.1);
}

.arrow {
    position: relative;
}
.arrow_left {
    position: absolute;
    left: 0;
    top: 150px;
    background-color: var(--lightviolet-color);
    color: var(--text-color-white);
}
.arrow_right {
    position: absolute;
    right: 0;
    top: 150px;
    background-color: var(--lightviolet-color);
    color: var(--text-color-white);
}
</style>