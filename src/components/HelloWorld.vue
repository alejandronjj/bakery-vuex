<template>
  <div class="hello">


        <section id="content">
            
            <article class="article">
                <h1>Bienvenidos, gatos</h1>
                <h2>Menú de Pasteles</h2>
                <div class="menuitem">
                  <p>Pastel 3 leches</p><p>$666</p>
                </div>

                <div class="menuitem">
                  <p>Pastel Chocolate</p><p>$666</p>
                </div>

                <div class="menuitem">
                  <p>Pastel Zarzamore</p><p>$666</p>
                </div>

                <div class="menuitem">
                  <p>Pastel Naranja</p><p>$666</p>
                </div>

                <div class="menuitem">
                  <p>Pastel Fresa</p><p>$666</p>
                </div>

                <div class="menuitem">
                  <p>Pastel Durazno</p><p>$666</p>
                </div>

                <div class="menuitem">
                  <p>Pastel Cacao</p><p>$666</p>
                </div>

                <div class="menuitem">
                  <p>Pastel Chocolate sin azúcar</p><p>$666</p>
                </div>

                <div class="menuitem">
                  <p>Pastel Bonito</p><p>$666</p>
                </div>
                
            </article>

            <article class="article">
                <h2>Adornos</h2>
                <div class="menuitem">
                  <p>Adorno vela</p><p>$8888</p>
                </div>

                <div class="menuitem">
                  <p>Adorno Pirotecnia</p><p>$8888</p>
                </div>

                <div class="menuitem">
                  <p>Adorno Nave</p><p>$8888</p>
                </div>

                <div class="menuitem">
                  <p>Adorno Águila</p><p>$8888</p>
                </div>

                <div class="menuitem">
                  <p>Adorno Cerillo</p><p>$8888</p>
                </div>

                <div class="menuitem">
                  <p>Adorno Veladora</p><p>$7777</p>
                </div>

                <div class="menuitem">
                  <p>Adorno Grande</p><p>$7777</p>
                </div>

                <div class="menuitem">
                  <p>Adorno Spiderman</p><p>$7777</p>
                </div>

                <div class="menuitem">
                  <p>Adorno Bonito</p><p>$7777</p>
                </div>

                <div class="menuitem">
                  
                </div>
                
                
                
                
                
                
                
                
                
                

            </article>

            <article class="article">
              <router-link to="/orden"><input type="button" value="Realizar Pedido"></router-link>
            </article>

        </section>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.menuitem{
  display: flex;
  width: 50%;
  justify-content: space-between;
}
</style>
