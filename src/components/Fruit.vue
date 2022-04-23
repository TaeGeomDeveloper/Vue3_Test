<template>
  <li>{{name}}?!</li>
</template>


<script>
export default {
  props: {
    name: {
        type: String,
        default: ''
    }
  }
}
</script>

// 유효범위 scoped
<style scoped lang="scss">
  h1 {
    color: red !important;
  }

</style>