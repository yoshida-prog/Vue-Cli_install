<template>
  <div id="app">
    {{ hello }}
  </div>
</template>

<script>

export default {
  name: '#app',
  data(){
    return{
      hello: 'Hello, World!'
    }
  }
}

</script>

<style>
#app {
  color: red
}
</style>
