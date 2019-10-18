<template lang="html">
  <div>
    <Header />
    <slider />
  </div>
</template>

<script>
import Header from '../public/header'
import slider from './hSlider'
export default {
  components: { Header, slider },
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
