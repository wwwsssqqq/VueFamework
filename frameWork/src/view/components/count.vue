<template lang="pug">
  .demo
    h2 {{msg}}
    hr
    h3 {{$store.state.count}}
    .btn-box
      button(@click="$store.commit('add')") 加
      button(@click="$store.commit('reduce')") 减
</template>

<script>
  import store from '@/store/store'
  export default{
    components: {
      store
    },
    data () {
      return {
        msg: 'hello vuex'
      }
    }
  }
</script>