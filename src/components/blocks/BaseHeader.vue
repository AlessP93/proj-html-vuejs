<template>
  <header>
    <div class="container-fuid">
        <div class="row">
            <div class="col">
                <div class="logo_header">
                    <img src="../../assets/img/avada-bakery-logo-retina-200x97.png" alt="">
                </div>
                <div class="nav_header">
                    <ul>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li> 
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li> 
                        <li><a href="#">link</a></li>
                        <li><a href="#">link</a></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-4">
                <div class="text_hero">
                    <small>FRESH & TASTY BAKERY EVERY DAY</small>
                    <h1>The Perfect Fresh Bread</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit praesentium veniam consequatur quo Lorem ipsum dolor sit amet consectetur.</p>
                </div>
                <button class="--primary-btn"></button>
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
header {
    background-color: rgb(255, 213, 219);
    min-height: 31.25rem;
    color: #55328b;

    .col {
        display: flex;
        justify-content: space-between;
        margin: 0 .625rem;
    }
    .logo_header img {
        width: 100px;
    }
}

.nav_header {
    align-self: end;
}
.nav_header ul {
    display: flex;
    
    li {
        margin-right: 15px;
        list-style: none;
        font-size: .8125rem;

        a {
            text-decoration: none;
        }
    }
}

.text_hero {
    margin: 3.125rem 1.875rem;
}
</style>