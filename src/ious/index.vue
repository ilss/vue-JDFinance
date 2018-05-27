 <template>
    <div>
        <Heador/>
        <Slider/>
        <Welfare/>
        <Service/>
        <Footer />
        <Navbar/>
    </div>
</template>

<script>
import Heador from '../public/header'
import Slider from './islider'
import Footer from '../public/footer'
import Navbar from '../public/navbar'
import Welfare from './welfare'
import Service from './service'
export default {
    components: {
        Heador,
        Slider,
        Footer,
        Navbar,
        Welfare,
        Service,
    },
}
</script>

<style lang='scss'>
</style>