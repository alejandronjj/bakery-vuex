<template>
  <div class="home">
    
    <HelloWorld/>
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
*{
    background-image: linear-gradient(rgba(0, 0, 0, 0.7),rgba(0, 0, 0, 0.7)),url(https://raw.githubusercontent.com/alejandronjj/bakery.vuex/main/src/assets/backkk.jpg);
    min-height: 500px;
    width: 100%;
    padding: 30px;
    color: aliceblue;
    background-size: cover;
}

.home{
  width: 93.7vw;
  padding: 0;
  margin: 0;
}
</style>
