<template>
  <main>
    <div class="container py-5">
        <div class="row">
            <div class="col-4">
                <div class="text_hero_one">
                    <small>OUR PRODUCTS</small>
                    <h4>All our delectables pastries are backed fresh in our Kitchen every morning, and are made with all-natural, all organic ingredients.</h4>
                    <button class="secondary_btn">Start Shopping</button>
                </div>
            </div>
            <div class="col-4">
                <div class="img_slot">
                    <img src="../../assets/img/choco-chip-cookies.jpg" alt="">
                </div>
            </div>
            <div class="col-4">
                <div class="img_slot">
                    <img src="../../assets/img/strawberry-jam-cookies.jpg" alt="">
                </div>
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
    }

    h4 {
        color: var(--text-color-violet);
    }
}
.img_slot img {
        width: 100%;
    }
</style>