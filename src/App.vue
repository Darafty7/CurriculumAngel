<template>
  <main>
    <nav>

      <p class="Nombrepro">Angel Arley Cantero</p>

      <router-link to="/SobreMi">Sobre Mi</router-link> |
      <router-link to="/Curriculum">Curriculum</router-link> |
      <router-link to="/Proyecto">Proyecto</router-link> |
      <router-link to="/Contacto">Contacto</router-link>
    </nav>
    <router-view/>
  </main>

</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}


.Nombrepro{
  position: relative;
right: 460px;
top:9px;
font-weight: bold;
color: rgb(232, 136, 104);
}

nav a {
  text-decoration: none;
  font-weight: bold;
  color: #2c3e50;
}
</style>
