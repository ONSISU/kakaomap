<template>
  <KakaoMap/>
</template>

<script>
import KakaoMap from './components/KakaoMap.vue'

export default {
  name: 'App',
  components: {
    KakaoMap
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
