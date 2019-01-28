<template>
    <div class="hello">
        <h1>{{ msg }}</h1>
        <h3><a href="index.html">Index</a></h3>
    </div>
</template>

<script>
export default {
  name: 'cell',
  data () {
    return {
      msg: '多页面测试'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>