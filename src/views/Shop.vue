<template>
    <div class="shop flex-container flex-dir-column">
        <headerShop />
        <productsAll />
    </div>
</template>

<script>

import headerShop from '../components/shop/header'
import productsAll from '../components/shop/productsAll'

export default {
    name: 'shop',
    components:{
        headerShop,
        productsAll
    }
}
</script>

<style scoped>

img{
    min-height: 180px;
}

.home-header{
    position: relative;
    justify-content: center;
    align-items: center;
}
.title-header{
    position: absolute;
}
.shadow{
    position: absolute;
    width: 100%;
    height: 100%;
    z-index: 2;
    background-color: #000000ad;
}
.title-header{
    color: white;
    z-index: 3;
    margin: 0px 20%;
}
.title-logo{
    margin-right: 10px;
}
.title-logo{
    text-align: center;
    font-family: 'Great Vibes', cursive;
}
span{
    font-family: "Helvetica Neue",Helvetica,Roboto,Arial,sans-serif;
    font-size: 28px;
}
</style>
