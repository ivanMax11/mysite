<template>
<div class="grid"> 
    <div class="project-flex">
      <div class="project-item">
        <img id="projects" src="../assets/layouts.png" alt="">
        <a href="https://ivanmax11.github.io/wdd230/week1/holygrail.html">Layouts</a>
      </div>
      <div class="project-item">
        <img id="projects" src="../assets/DesignPrinciples.png" alt="">
        <a href="https://ivanmax11.github.io/wdd230/week2/design.html">Web Design Principles</a>
      </div>
      <div class="project-item">
        <img id="projects" src="../assets/Barber.png" alt="">
        <a href="https://ivanmax11.github.io/BarberShop/BarberShop/">BarberShop</a>
      </div>
      <div class="project-item">
        <img id="projects" src="../assets/MiniAlura.png" alt="">
        <a href="https://ivanmax11.github.io/OneNext/MiniAlura/">Mini Alura</a>
      </div>
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

<style scoped>
.grid {
  background: linear-gradient(to right, #001551, #00effb );
}

.project-flex {
  display: flex;
  flex-wrap: wrap; 
  justify-content: center;
}

a {
    color: #5d92ad;
  }

.project-item {
  width: 250px;
  height: 170px;
  background-color: white;
  border-radius: 15px;
  text-align: center;
  margin: 10px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

#projects {
  width: 200px;
  height: 100px;
  border-radius: 15px;
}

.project-item a {
  display: block; 
  margin-top: 5px; 
}
</style>

<script setup> 

</script>