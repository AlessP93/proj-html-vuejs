<template>
  <section>
    <div class="container py-5">
        <div class="row">
            <div class="col-12 text-center">
                <small>LOCATIONS</small>
                <h2>Visit our Bakeries</h2>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="baking_ny col-6"></div>
            <div class="baking_ld col-6"></div>
        </div>
    </div>
    <div class="container">
        <div class="row text-center">
            <div class="ny_color col-6">
                <h2 class="py-3">New York</h2>
                <div class="row">
                    <div class="col-4 py-3">
                        <div>CALL US</div>
                        <span>1.800.458.556</span>
                    </div>
                    <div class="col-4 py-3">
                        <div>OPEN ALL WEEKS</div>
                        <span>9:00 AM - 6:00 PM</span>
                    </div>
                    <div class="col-4 py-3">
                        <button class="primary_btn">View Map</button>
                    </div>
                </div>
            </div>
            <div class="ld_color col-6">
                <h2 class="py-3">London</h2>
                <div class="row">
                    <div class="col-4 py-3">
                        <div>CALL US</div>
                        <span>1.800.458.556</span>
                    </div>
                    <div class="col-4 py-3">
                        <div>OPEN ALL WEEKS</div>
                        <span>9:00 AM - 6:00 PM</span>
                    </div>
                    <div class="col-4 py-3">
                        <button class="primary_btn">View Map</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container py-5">
        <div class="row justify-content-between">
            <div class="bakery_one col-3"></div>
            <div class="bakery_two col-5 text-center py-5">
                <small class="py-5">MADE FOR SHARING</small>
                <h2 class="py-5">Let's stay in touch</h2>
                <button class="secondary_btn">
                    <i class="fa-brands fa-instagram"></i>Follow Us
                </button>
            </div>
            <div class="bakery_three col-3"></div>
        </div>
    </div>
    <div class="container">
        <div class="row justify-content-between">
            <div class="bakery_four col-2"></div>
            <div class="bakery_five col-2"></div>
            <div class="bakery_six col-2"></div>
            <div class="bakery_seven col-2"></div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'sectionFour'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/buttons/buttons.scss';

h2 {
    color: var(--text-color-violet);
}

small {
    color: var(--text-color-grey);
}

div, span {
    color: var(--text-color-grey);
}
.baking_ny {
    background-image: url('../../assets/img/new-york-bk.jpg');
    background-size: cover;
    height: 400px;
}

.ny_color {
    background-color: var(--lightazure-color);
}
.baking_ld {
    background-image: url('../../assets/img/london-bk.jpg');
    background-size: cover;
    height: 400px;
}
.ld_color {
    background-color: var(--lightyellow-color);
}
.bakery_one {
    background-image: url(../../assets/img/social-1.jpg);
    background-size: cover;
    height: 300px;
    width: 23%;
}

.bakery_two {
    background-color: var(--lightgrey-color);
    height: 300px;
    width: 49%;
}

.bakery_three {
    background-image: url('../../assets/img/social-2.jpg');
    background-size: cover;
    height: 300px;
    width: 23%;
}

.bakery_four {
    background-image: url('../../assets/img/social-3.jpg');
    background-size: cover;
    height: 300px;
    width: 23%;
}
.bakery_five {
    background-image: url('../../assets/img/social-4.jpg');
    background-size: cover;
    height: 300px;
    width: 23%;
}
.bakery_six {
    background-image: url('../../assets/img/social-5.jpg');
    background-size: cover;
    height: 300px;
    width: 23%;
}
.bakery_seven {
    background-image: url('../../assets/img/social-6.jpg');
    background-size: cover;
    height: 300px;
    width: 23%;
}
</style>