<template>

<div class="container">
        <h1>Seleccione el sabor del pastel y cantidad</h1>
        <div class="boxes">
        <input type="checkbox" id="3leches" name="3leches" value="3leches">
        <label for="3leches">Tres leches</label>
        <input type="number" id="3lechescuantos" name="3lechescuantos">
        </div>

        <div class="boxes">
        <input type="checkbox" id="Chocolate" name="Chocolate" value="Chocolate">
        <label for="Chocolate">Chocolate</label>
        <input type="number" id="Chocolatecuantos" name="Chocolatecuantos">
        </div>

        <div class="boxes">
        <input type="checkbox" id="Zarzamore" name="Zarzamore" value="Zarzamore">
        <label for="Zarzamore">Zarzamore</label>
        <input type="number" id="Zarzamorecuantos" name="Zarzamorecuantos">
        </div>

        <div class="boxes">
        <input type="checkbox" id="Naranja" name="Naranja" value="Naranja">
        <label for="Naranja">Naranja</label>
        <input type="number" id="Naranjacuantos" name="Naranjacuantos">
        </div>

        <div class="boxes">
        <input type="checkbox" id="Fresa" name="Fresa" value="Fresa">
        <label for="Fresa">Fresa</label>
        <input type="number" id="Fresacuantos" name="Fresacuantos">
        </div>

        <div class="boxes">
        <input type="checkbox" id="Durazno" name="Durazno" value="Durazno">
        <label for="Durazno">Durazno</label>
        <input type="number" id="Duraznocuantos" name="Duraznocuantos">
        </div>

        <div class="boxes">
        <input type="checkbox" id="Cacao" name="Cacao" value="Cacao">
        <label for="Cacao">Cacao</label>
        <input type="number" id="Cacaocuantos" name="Cacaocuantos">
        </div>

        <div class="boxes">
        <input type="checkbox" id="chocolatesinazucar" name="chocolatesinazucar" value="chocolatesinazucar">
        <label for="chocolatesinazucar">Chocolate sin azucar</label>
        <input type="number" id="chocolatesinazucarcuantos" name="chocolatesinazucarcuantos">
        </div>

        <div class="boxes">
        <input type="checkbox" id="pastelbonito" name="pastelbonito" value="pastelbonito">
        <label for="pastelbonito">Pastel bonito</label>
        <input type="number" id="pastelbonitocuantos" name="pastelbonitocuantos">
        </div>

</div>
</template>

<style scoped>
*{
  margin: 0;
  padding: 0;
}

.container{
  width: 100%;
}
.boxes{
  display: flex;
  width: 52%;
  justify-content: space-between;
  padding: 5px 0px;
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
  name: 'sabores',
}
</script>