<template>
  <div>
    <test :data="data"></test>
  </div>
</template>

<script>
import Test from './lib/test.vue'
export default {
  props:{
    data: {
      type: String,
      default:''
    }
  },
  components:{
    Test
  }
}
</script>

<style>

</style>
