<template>
  <p>
    My name is Ivan Maximiliano Monte, <br />
    I am passionate about learning and I really like technology, <br />
    I enjoy reading and watching the latest trends. <br />
    I am a frontend developer and I am learning backend terrain to complete my
    degree, <br />
    however I am educated in everything that concerns computer technology. <br>
    Was born and right now living in Santiago del Estero, Argentina.
  </p>
  <div class="information">
    <ul id="inf">
      <h2>Profile</h2>
      <li>
        <h3>Full name:</h3>
        Ivan Maximiliano Monte
      </li>
      <li>
        <h3>Birth:</h3>
        07 November 1993
      </li>
      <li>
        <h3>Job:</h3>
        Freelance Frontend Developer
      </li>
      <li>
        <h3>Web Site</h3>
        sitioweb
      </li>
      <li>
        <h3>Email:</h3>
        ivanmonte11.07@iutlook.com
      </li>
    </ul>
    <img src="ivanProf.jpeg" alt="Photo Ivan" class="centered-image"/>
    <ul id="skills">
      <h2>Skills</h2>
      <li><h3>Markup and styling languages</h3></li>
      <li>HTML - CSS - SCSS</li>
      <li><h3>Programming Languages:</h3></li>
      <li>Python - JavaScript - C#</li>
      <li><h3>Technologies :</h3></li>
      <li>Nodejs - Express - Vuejs - Django - Bootstrap - Firebase</li>
      <li><h3>DataBase:</h3></li>
      <li>Postgres - SQLServer</li>
    </ul>
  </div>
</template>

<script setup></script>

<style scoped>
p {
    color: #00effb;
}

.information {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 20px;
  align-items: start;
  background: linear-gradient(to right, #001551, #00effb );
}

#inf,
#skills {
  text-align: left; /* Alinea el texto al comienzo dentro de ul */
}

#skills {
    color: white;
}

.centered-image {
  max-width: 100%;
  margin-top: 12px;
  display: block;
}

img {
  width: 300px;
  margin-left: 10%;
}

@media screen and (max-width: 768px) {
  .information {
    display: block;
    color: white;
     
  }

  img {
        margin-left: 30%;
        width: 250px;
      }

}
</style>
