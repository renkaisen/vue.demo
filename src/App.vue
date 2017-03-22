<template>
  <div id="app">
    <h3>牵着一头小鹿走</h3>
    <strong>{{ msg }}</strong>
    <input type="button" value="您快来点我，你好牛逼啊" @click = 'change'>
    <Hello></Hello>
  </div>
</template>

<script>
import Hello from './components/Hello.vue'

export default {
  data () {
    return {
      msg: '真的很niub'
    }
  },
  components: {
    Hello
  }
}

</script>

<style>
html {
  height: 100%;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

#app {
  color: #2c3e50;
  margin-top: -100px;
  max-width: 600px;
  font-family: Source Sans Pro, Helvetica, sans-serif;
  text-align: center;
}

#app a {
  color: #42b983;
  text-decoration: none;
}
strong{
  background: red;
}


</style>
