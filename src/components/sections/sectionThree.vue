<template>
  <section class="py-5">
   <div class="container sec_box_one">
        <div class="opacity_box p-5 d-flex justify-content-between flex-column">
            <div class="row">
                <div class="col-3">
                    <h3>Tell us what you have in mind</h3>
                </div>
                <div class="col-9 text-end">
                <span class="number_1">01</span>
                </div>
            </div>
            <div class="row space-between">
                <div class="col-8"></div>
                <div class="col-4">
                    <small>MANUAL INGREDIENTS SELECTION</small>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vel consequatur, voluptatem deleniti nesciunt distinctio perferendis a, modi ea libero corrupti tenetur mollitia dolorem? Magnam deleniti possimus sunt esse est quaerat.</p>
                </div>
            </div>
        </div>
    </div>
    <div class="container py-5">
        <div class="row justify-content-between">
            <div class="col-5 sec_box_two">
                <div class="opacity_box p-5 d-flex justify-content-between flex-column">
                    <div class="row">
                        <div class="col-8">
                            <h3>We Start Baking</h3>
                        </div>
                        <div class="col-4 text-end">
                            <span class="number_1">02</span>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-8">
                            <small>SWEET & DELICIUS</small>
                            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vel consequatur, voluptatem deleniti nesciunt distinctio perferendis a, modi ea libero corrupti tenetur mollitia dolorem.</p>
                        </div>
                        <div class="col-3"></div>
                    </div>
                </div>   
            </div>
            <div class="col-5 sec_box_three">
                <div class="row py-5">
                    <div class="col-12 p-5 justify-content-center">
                        <small>DONT JUST TAKE OUR WORD FOR IT</small>
                        <h3 class="py-5">"Finally found an alternative to the mass produced product. Something that incorporates real organic ingredients, nutrient dense wellness while promoting sustainability and activity."</h3>
                        <small class="py-5">Rachel Cooper, Founder</small>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container sec_box_four">
    <div class="opacity_box p-5 d-flex justify-content-between flex-column">
        <div class="row">
            <div class="col-4">
                <h3>Tell us what you have in mind</h3>
            </div>
            <div class="col-8 text-end">
            <span class="number_1">03</span>
            </div>
        </div>
            <div class="row space-between">
                <div class="col-4">
                    <small>MANUAL INGREDIENTS SELECTION</small>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vel consequatur, voluptatem deleniti nesciunt distinctio perferendis a, modi ea libero corrupti tenetur mollitia dolorem? Magnam deleniti possimus sunt esse est quaerat.</p>
                </div>
                <div class="col-8"></div>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name: 'sectionThree'
}
</script>

<style lang="scss" scoped>
.opacity_box {
    background-color: rgba(0, 0, 0, 0.4);
    width: 100%;
    height: 100%;
}
.sec_box_one {
    background-image: url('../../assets/img/bakery-process-1.jpg');
    background-size: cover;
    height: 500px;
    flex-direction: column;
    padding: 0;
    

    h3, p, span {
        color: var(--text-color-white);
    }
    small {
        color: var(--text-color-grey);
    }
    small, p {
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
}
.number_1 {
    font-size: 3.125rem;
    font-family: 'Segoe UI', Tahoma, Verdana, sans-serif;
    font-weight: lighter;
    }

.sec_box_two {
    background-image: url('../../assets/img/bakery-process-2.jpg');
    background-size: cover;
    height: 500px;
    color: var(--text-color-white);
    padding: 0;
    width: 48%;

    small {
        color: var(--text-color-grey);
    }
    small, p {
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
}

.sec_box_three {
    background-color: var(--lightgrey-color);
    height: 500px;
    width: 48%;

    h3 {
        color: var(--text-color-violet);
    }
    small {
        color: var(--text-color-grey);
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
}

.sec_box_four {
    background-image: url('../../assets/img/bakery-process-3.jpg');
    background-size: cover;
    height: 500px;
    flex-direction: column;
    padding: 0;

    h3, p, span {
        color: var(--text-color-white);
    }
    small {
        color: var(--text-color-grey);
    }
    small, p {
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
}
</style>