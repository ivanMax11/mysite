<template>
  <h2>My Featured Projects</h2>
  <div class="grid">
    <div class="project-flex">
      
      <div class="project-item">
        <img id="projects" src="../assets/Apeperia.png" alt="">
        <a href="https://ivanmax11.github.io/ApeperiaCommerce/">Apeperia Commerce</a>
      </div>
      <div class="project-item">
        <img id="projects" src="../assets/GameStore.png" alt="">
        <a href="https://ivanmax11.github.io/Store/GameStore/">Apeperia Commerce</a>
      </div>
      <div class="project-item">
        <img id="projects" src="../assets/chamber.png" alt="">
        <a href="https://ivanmax11.github.io/wdd230/chamber/index.html">Chamber of Commerce</a>
      </div>
      <div class="project-item">
        <img id="projects" src="../assets/nasaApp.png" alt="">
        <a href="https://ivanmax11.github.io/Challengewdd330/src/#">NASA API</a>
      </div>
     
    </div>
    
  </div>
</template>

<script setup>

</script>

<style scoped>
/* Estilos específicos del componente */

.grid {
  background: linear-gradient(to right, #001551, #00effb );
}

h2:hover {
  color: #00effb;
}

p {
  color: #fbc530;
}

.project-flex {
  display: flex;
  flex-wrap: wrap; 
  justify-content: center;
}

a {
    color: #3e7591;
  }

.project-item {
  width: 370px;
  height: 270px;
  border-radius: 15px;
  background-color: white;
  text-align: center;
  margin: 10px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#projects {
  width: 300px;
  height: 200px;
  border-radius: 15px;
}

.project-item a {
  display: block; 
  margin-top: 5px; 
}

@media screen and (max-width: 768px) {
  .project-flex {
    width: 200px;
    margin-left: 30%;
  }
}

</style>
