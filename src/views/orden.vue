<template>

<section id="content">

    <formulario/>



</section>
</template>

<style scoped>
*{
    
    width: 100%;
    padding: 0px;
    color: aliceblue;
    background-size: cover;
}

#content{
    background-image: linear-gradient(rgba(0, 0, 0, 0.7),rgba(0, 0, 0, 0.7)),url(https://raw.githubusercontent.com/alejandronjj/bakery.vuex/main/src/assets/backkk.jpg);
   
    min-height: 100vh;
    width: 100%;
    margin: 0;
    color: aliceblue;
    border: 0;
}

input{
    height: 10px;
    width: 50px;
}


</style>

<script>
import formulario from "../components/formulario.vue";

export default {
  name: 'orden',
  components:{
      formulario,

    }
}
</script>
