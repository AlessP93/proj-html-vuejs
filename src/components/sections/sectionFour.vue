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
                          <span>CALL US</span>
                        <p>1.800.458.556</p>
                    </div>
                    <div class="col-4 py-3">
                      <span>OPEN ALL WEEKS</span>
                        <p>9:00 AM - 6:00 PM</p>
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
                        <span>CALL US</span>
                        <p>1.800.458.556</p>
                    </div>
                    <div class="col-4 py-3">
                        <span>OPEN ALL WEEKS</span>
                        <p>9:00 AM - 6:00 PM</p>
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
                <button class="secondary_btn"><i class="fa-brands fa-instagram"></i>Follow Us</button>
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
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

span, p {
    color: var(--text-color-grey);
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.baking_ny {
    background-image: url('../../assets/img/new-york-bk.jpg');
}
.ny_color {
    background-color: var(--lightazure-color);
}
.baking_ny, .baking_ld {
    background-size: cover;
    height: 400px;
}
.baking_ld {
    background-image: url('../../assets/img/london-bk.jpg');
}
.ld_color {
    background-color: var(--lightyellow-color);
}
.bakery_one, .bakery_three, .bakery_four, .bakery_five, .bakery_six, .bakery_seven {
    background-size: cover;
    height: 300px;
    width: 23%;
}
.bakery_one {
    background-image: url(../../assets/img/social-1.jpg);
}
.bakery_two {
    background-color: var(--lightgrey-color);
    height: 300px;
    width: 49%;
}
.bakery_three {
    background-image: url('../../assets/img/social-2.jpg');
}
.bakery_four {
    background-image: url('../../assets/img/social-3.jpg');
}
.bakery_five {
    background-image: url('../../assets/img/social-4.jpg');
}
.bakery_six {
    background-image: url('../../assets/img/social-5.jpg');
}
.bakery_seven {
    background-image: url('../../assets/img/social-6.jpg');
}
.primary_btn {
    transition: transform 2s;
    box-shadow: -10px 10px 20px rgba(0, 0, 0, 0.4);
}
.primary_btn:hover {
    transform: scale(1.1);
}
.secondary_btn {
    transition: transform 2s;
    box-shadow: -10px 10px 20px rgba(100, 0, 133, 0.625);
}
.secondary_btn:hover {
    transform: scale(1.1);
}
</style>