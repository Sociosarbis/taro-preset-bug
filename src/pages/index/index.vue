<template>
  <view class="index">
    <text>{{ msg }}</text>
    <A />
  </view>
</template>

<script>
import { ref } from 'vue'
import './index.css'
import A from './A'

export default {
  components: {
    A
  },
  setup () {
    const msg = ref('Hello world')
    return {
      msg
    }
  }
}
</script>
