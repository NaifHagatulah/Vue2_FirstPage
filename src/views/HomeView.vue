<template>
  <div class="home">
    <p>this will not be styled</p>
    <HelloWorld msg="Hello world"/>
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
<style scoped>
p{
  color: blue;
}
</style>