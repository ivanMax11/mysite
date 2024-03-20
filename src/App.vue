<template lang="en">
  <header class="headerSite">
    <div class="description">      
      <h1 class="nameTitle">Ivàn Maximiliano Monte | Frontend Developer</h1><hr>
    </div>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About me</router-link> |
      <router-link to="/projects">Portfolium</router-link> |
      <router-link to="/resume">Resume</router-link>
    </nav>
  </header>
   
  <router-view/>
  <footer>
        <p>&copy;2024 Ivan Maximiliano Monte | All rights reserved</p> 
        <a href="https://www.facebook.com/profile.php?id=61554865662152"><img src="../public/fcb.png" alt="fcbk icon"></a>
        <a href="https://www.instagram.com/ivan.maxdev/"><img src="../public/insta.png" alt="instagram icon"></a>
        <a href="https://www.linkedin.com/in/ivan-maximiliano-monte/"><img src="../public/link.png" alt="linkedin icon"></a>
        
    </footer>
</template>

<style lang="scss"> 
@font-face {
  font-family: 'Anta'; // Nombre que le darás a tu fuente
  src: url('../fonts/Anta.ttf') format('truetype'); // Ruta de tu fuente
  font-weight: normal;
  font-style: normal;
}

#app {
  font-family: 'Anta', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:  #4db872;
  
}

#vue {
  width: 100px;
  text-align: center;
}

body {
  background-color: #00203d;
}

.headerSite {
  display: grid;
  grid-template-columns: auto 1fr;
  align-items: center;
}

.headerSite {
  display: grid;
  grid-template-columns: auto 1fr;
  align-items: center;

  @media screen and (max-width: 768px) {
    grid-template-columns: 1fr; /* Cambia a una sola columna en dispositivos más pequeños */
    text-align: center; /* Centra los elementos en dispositivos más pequeños */
  }
}

.description img {
  grid-column: 1;
  width: 250px;
  margin-right: 20px; /* Reduzco el margen derecho en dispositivos más pequeños */
  margin-bottom: 10px; /* Agrego un margen inferior para separar la imagen del texto */
  border-radius: 15px;
}

.nameTitle {
  grid-column: 1; /* Centra el título en dispositivos más pequeños */
  margin-bottom: 20px; /* Agrega espacio entre el título y el menú de navegación */
}

nav {
  font-size: large;
  display: flex; /* Cambio a un diseño de flexbox */
  justify-content: center; /* Centra los enlaces en dispositivos más pequeños */
  gap: 10px; /* Agrega espacio entre los enlaces */

  a {
    font-weight: bold;
    color: #4db872;

    &.router-link-exact-active {
      color: #00eaf7;
    }
  }

  @media screen and (max-width: 768px) {
    flex-direction: column; /* Cambia a una columna en dispositivos más pequeños */
    align-items: center; /* Centra los enlaces verticalmente */
  }
}

footer {
  display: flex;
  justify-content: center; /* Centra los elementos en dispositivos más pequeños */
  gap: 10px; /* Agrega espacio entre los elementos */

  img {
    width: 30px;
    margin-top: 10px;
  }
}


</style>
