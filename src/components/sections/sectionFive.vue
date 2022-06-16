<template>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-5 p-5">
                    <small class="py-5">TRY OUR SEASONAL PRODUCT</small>
                    <h2  class="py-4">Order for pick-up or delivery to your home</h2>
                    <span class="py-5"><button class="primary_btn">Shop Now</button></span>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'sectionFive'
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/buttons/buttons.scss';

section {
    background-image: url(../../assets/img/call-to-action-bg.jpg);
    background-size: cover;
    height: 21.875rem;
    margin-top: 5rem;
    
    small {
        color: var(--text-color-grey);
    }
    h2 {
        color: var(--text-color-white);
    }
}

</style>