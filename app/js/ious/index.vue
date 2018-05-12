<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Finance/>
        <More/>
        <Footor/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Footor from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
import Slider from './islider.vue'
import Finance from './finance.vue'
import More from './More.vue'

export default {
  components:{
    Heador,
    Footor,
    Navbar,
    Slider,
    Finance,
    More,
  }
}
</script>
<style lang="scss">

</style>
