<template>
  <div class="bg-black h-full">
    <navigation id="navigation"></navigation>
  </div>
</template>

<script>
import { defineProps, reactive } from 'vue'
import navigation from '../components/nav.vue'

export default {
  components: { navigation }
}
defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<style scoped>
a {
  color: #42b983;
}
#navigation{
  width: 19.84375%;
}
</style>
