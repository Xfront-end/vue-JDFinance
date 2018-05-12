<template lang="html">
    <section :class="$style.content">
      <Slider :items="items" :cname="$style.slider"/>
    </section>
</template>

<script>
//import Panel from '../core/panel.vue'
import Slider from '../core/slider.vue'
export default {
  components:{
    Slider,
  },
  data(){
    return {
      items:[{
        href: 'money',
        img: '//img12.360buyimg.com/jrpmobile/jfs/t19087/201/1952941995/49031/f0f213c8/5addc4b1N07ba5c08.jpg?width=750&height=400',
      },{
        href: 'money',
        img: '//img12.360buyimg.com/jrpmobile/jfs/t19690/182/1909914430/49554/80cbbe8b/5addc4c2Nb9b1a20d.jpg?width=750&height=400',
      },{
        href: 'money',
        img: '//img12.360buyimg.com/jrpmobile/jfs/t17044/72/1905017687/57902/9229137c/5addc4d2N28eeac2f.jpg?width=750&height=400',
      },{
        href: 'money',
        img: '//img12.360buyimg.com/jrpmobile/jfs/t17671/227/1922535978/60213/a0585c59/5addc4e2N11bdd0ef.png?width=750&height=400',
      }]
    }
  }
}
</script>

<style lang="scss" module>
  @import "../../css/element.scss";

    .content{
      .slider{
        margin-top: 100px;
      }
    }
</style>
