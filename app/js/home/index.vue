<template lang="html">
  <div>
    <Header />
    <slider />
    <novice />
    <borrow />
    <money />
    <product />
    <life />
  </div>
</template>

<script>
import Header from '../public/header'
import slider from './hSlider'
import novice from './novice'
import borrow from './borrow'
import money from './money'
import product from './product'
import life from './life'

export default {
  components: { Header, slider, novice, borrow, money, product, life },
  data() {
    return {}
  },
  created() {
    let a = 1
  }
}
</script>

<style lang="scss" module>
@import "../../css/reset.scss";
.home {
  color: red;
  font-size: 80px;
}
</style>
