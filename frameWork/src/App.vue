<template lang="pug">
  #app
    //- count
    <router-view></router-view>
</template>

<script>
  // import count from '@/view/components/count'
export default {
    // components: {count}
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
