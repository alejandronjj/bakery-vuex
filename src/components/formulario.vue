<template>
<section id="content">
            
 <form action="pedido.js">

  <Datoscliente/>
  <sabores/>
  <adornos/>

  <br><br>
  <input type="reset">
  <input type="submit">
  <br><br>



 </form>
            
</section>

</template>


<style scoped>
*{
  padding: 20px;
}


</style>



<script>

import Datoscliente from "../components/datoscliente.vue";
import sabores from "../components/sabores.vue";
import adornos from "../components/adornos.vue";
export default {
  name: 'formulario',
  components:{
      Datoscliente,
      sabores,
      adornos,
  }
}
</script>