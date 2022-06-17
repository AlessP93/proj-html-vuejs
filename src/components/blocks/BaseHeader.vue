<template>
    <header>
        <div class="container">
            <div class="row">
                <div class="col-4">
                    <div class="text_hero">
                        <small>FRESH & TASTY BAKERY EVERY DAY</small>
                        <h1>The Perfect Fresh Bread</h1>
                        <p class="py-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit praesentium veniam consequatur quo Lorem ipsum dolor sit amet consectetur.</p>
                        <button class="primary_btn">Explore our products</button>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<script>

export default {
name: 'BaseHeader',
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/buttons/buttons.scss';

header {
    background-image: url('../../assets/img/bakery_demo.png');
    background-size: cover;
    background-position: center;
    height: 40.625rem;
}
.text_hero {
    margin: 9.375rem 1.875rem;

    small, p {
        color: var(--text-color-grey);
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }

    h1 {
        color: var(--text-color-violet);
    }
}

.primary_btn {
    transition: transform 2s;
    box-shadow: -10px 10px 20px rgba(0,0,0,0.4);
}
.primary_btn:hover {
    transform: scale(1.1);
}
</style>