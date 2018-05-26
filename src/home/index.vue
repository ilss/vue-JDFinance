<template>
    <div>
        <Heador/>
        <Slider/>
        <Novice/>
    </div>
</template>

<script>
import Heador from '../public/header'
import Slider from './hslider'
import Novice from './novice'
export default {
    components: {
        Heador,
        Slider,
        Novice,
    },
}
</script>

<style lang='scss' scoped>
@import "../css/reset.scss";
</style>