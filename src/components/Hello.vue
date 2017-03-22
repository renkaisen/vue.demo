<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>会是小鹿</h3>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: '我学习中的，vue 这个规范好难受!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: #42b983;
}
</style>
