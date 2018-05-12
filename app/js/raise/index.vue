<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Daily/>
        <In/>
        <Welfare/>
        <Footor class="mfooter"/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from '../public/header.vue';
import Footor from '../public/footer.vue';
import Navbar from '../public/navbar.vue';
import Slider from './rslider.vue';
import Daily from './daily.vue';
import In from './in.vue'
import Welfare from './welfare.vue'
// import Finance from './finance.vue'
// import AdThird from './adThird.vue'

export default {
  components:{
    Heador,
    Footor,
    Navbar,
    Slider,
    Daily,
    In,
    Welfare,
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
