<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <AdFirst/>
        <Money/>
        <AdSecond/>
        <Finance/>
        <AdThird/>
        <Footor class="mfooter"/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Footor from '../public/footer.vue'
import Navbar from '../public/navbar.vue'
import Slider from './mslider.vue'
import AdFirst from './adFirst.vue'
import Money from './money.vue'
import AdSecond from './adSecond.vue'
import Finance from './finance.vue'
import AdThird from './adThird.vue'

export default {
  components:{
    Heador,
    Footor,
    Navbar,
    Slider,
    AdFirst,
    Money,
    AdSecond,
    Finance,
    AdThird
  }
}
</script>
<style lang="scss">
  .mfooter{
    li:nth-child(1){
      display: none;
    }
  }
</style>
