<template>
<h1>Datos del cliente</h1>
<div class="container">
  

  <div class="boxes">
    <label for="nombre">Nombre: &nbsp;</label>
    <input type="text" id="nombre" name="nombre" placeholder="Louis Armstrong"><br>
  </div>

<div class="boxes">
<label for="telefono">Teléfono:&nbsp; </label>
<input type="tel" id="telefono" name="telefono" placeholder="5512345678" maxlength="10"><br>
</div>
<div class="boxes">
<label for="email">email: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </label>
<input type="email" id="email" name="email" placeholder="gato@outlook.com"><br><br><br>
</div>
        
</div>

</template>

<style scoped>
.container{
  width: 100%;
}
.boxes{
  display: flex;
  width: 50%;
  justify-content: space-between;
}

input{
  height: 20px;
}

h1{
  padding: 10px;
}


</style>



<script>
export default {
  name: 'Datoscliente',
}
</script>