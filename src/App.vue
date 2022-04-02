<template>
  

  <header>
    <img alt="Bakery logo" src="https://raw.githubusercontent.com/alejandronjj/bakery.vuex/main/src/assets/gato.png">
    <h1>Pastelería El Gato Triste (y azul)</h1>
  </header>
  <nav>
    <router-link to="/">Menú</router-link>|
    <router-link to="/administrador">Administrador</router-link>|
    <router-link to="/contacto">Contáctanos</router-link>
    <router-link to="/orden">Realizar pedido</router-link>
    
    
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;
}
*{
    margin: 0;
    padding: 0;
    
}

img{
  width: 100px;
  height: 100px;
}

header{
    
    background-image: linear-gradient(rgba(69, 2, 2, 0.7),rgba(69,0,0,0.7)),url(./assets/Basically-Coffee-0219-03.jpg);
    width: 100%;
    text-align: left;
    color: whitesmoke;
    background-position: center;
    background-size: cover;
    display: flex;
    justify-content: left;
    align-items: center;
    
}

nav {
  padding: 30px;
  background-image: linear-gradient(rgba(0, 0, 0, 0.7),rgba(0, 0, 0, 0.7)),url(./assets/bardots.png);
  height:20px;
  display: flex;
  padding: 2% 6%;
  justify-content: left;
  align-items: center;
  flex: 1;
  text-align: right;
}

nav a {
  font-weight: bold;
  color: #ffffff;
  text-decoration: none;
  padding-right: 10px;
}

nav a.router-link-exact-active {
  color: #4274b9;
}
</style>
