<template>
    <div>
        <Heador/>
        <Slider/>
        <Novice/>
        <Borrow/>
        <Money/>
        <Product/>
        <Life/>
        <Footer/>
    </div>
</template>

<script>
import Heador from '../public/header'
import Slider from './hslider'
import Novice from './novice'
import Borrow from './borrow'
import Money from './money'
import Product from './product'
import Life from './life'
import Footer from '../public/footer'
export default {
    components: {
        Heador,
        Slider,
        Novice,
        Borrow,
        Money,
        Product,
        Life,
        Footer,
    },
}
</script>

<style lang='scss'>
@import "../css/reset.scss";
</style>