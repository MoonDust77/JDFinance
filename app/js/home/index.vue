<template lang="html">
  <div :class="$style.home">
    <h1>Home</h1>
  </div>
</template>

<script>
export default {
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
