<template>
  <div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Title/>
    <Jumbo/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Title from './components/Title.vue'
import Jumbo from '/components/Jumbo.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Title,
    Jumbo,
  }
}
</script>

<style lang="scss">

</style>
