<template>
  <div class="home">
      <div id="d1">

      </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style lang="less" scoped>
#d1{
  width:3.75rem;
  height: 3.75rem;
  background: cadetblue;
}
</style>