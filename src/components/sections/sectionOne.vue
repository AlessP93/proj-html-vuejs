<template>
  <main>
    <div class="container py-5">
        <div class="row justify-content-around">
            <div class="col-4">
                <div class="text_hero_one">
                    <small>OUR PRODUCTS</small>
                    <h4 class="mb-5 mt-2">All our delectables pastries are backed fresh in our Kitchen every morning, and are made with all-natural, all organic ingredients.</h4>
                    <span><button class="secondary_btn">Start Shopping</button></span>
                </div>
            </div>
            <div class="img_slot_one col-4">
                <span><i class="arrow_left fa-solid fa-angle-left"></i></span>
            </div>
            <div class="img_slot_two col-4">
                <span><i class="arrow_right fa-solid fa-angle-right"></i></span>
            </div>
        </div>
    </div>
  </main>
</template>

<script>
export default {
    name: 'sectionOne',
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/buttons/buttons.scss';
.text_hero_one {
    margin: 0 1.875rem;

    small {
        color: var(--text-color-grey);
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }

    h4 {
        color: var(--text-color-violet);
    }
}
.img_slot_one {
    background-image: url('../../assets/img/choco-chip-cookies.jpg');
}
.img_slot_two {
    background-image: url('../../assets/img/strawberry-jam-cookies.jpg');
}
.img_slot_one, .img_slot_two {
    background-size: cover;
    background-position: center;
    height: 400px;
    width: 32%;
    position: relative;
}

.secondary_btn {
    transition: transform 2s;
    box-shadow: -10px 10px 20px rgba(100, 0, 133, 0.625);
}
.secondary_btn:hover {
    transform: scale(1.1);
}
.arrow_left {
    position: absolute;
    left: 0;
    top: 200px;
    background-color: var(--lightviolet-color);
    color: var(--text-color-white);
}
.arrow_right {
    position: absolute;
    right: 0;
    top: 200px;
    background-color: var(--lightviolet-color);
    color: var(--text-color-white);
}
</style>