<script setup lang="ts">
import photo from "@/assets/img/avatar_g2.jpg";
import jhord from "@/assets/img/jhordeibys.jpeg";
import cer03 from "@/assets/img/logocer03.jpeg";
import torta80 from "@/assets/img/torta80.jpeg";
import pokemon from "@/assets/img/pokemon.png";
const { showNav } = useNavBar();

const handleOpenNav = () => {
  showNav.value = true;
}
</script>

<template>
   <!-- Header -->
  <header id="portfolio">
    <a href="#"><img :src="jhord" style="width:65px;" class="w3-circle w3-right w3-margin w3-hide-large w3-hover-opacity"></a>

    <!-- logo menu-->
    <span class="w3-button w3-hide-large w3-xxlarge w3-hover-text-grey" @click="handleOpenNav()"><i class="fa-solid fa-bars fa-lg"></i></span>

    <div class="w3-container w3-center">
      <h1><b>Jhordeibys Gabriel Da Silva Raaz</b></h1>
      <h2><b>Fullstack Developer </b></h2>
    </div>

  </header>
  
  <!-- First Photo Grid-->
  <div class="w3-row-padding w3-padding-large">
    <h4><b>Projects</b></h4>
    <div class="w3-third w3-container w3-margin-bottom">
      <a href="https://tortas-80-golpes-web.cp.murrudev.com/" target="_blank">
        <img :src="torta80" alt="Norway" class="w3-hover-opacity imgProjects">
      </a>
      <div class="w3-container w3-white">
        <p><b>Tortas 80 Golpes</b></p>
        <p>Web application for the sale of cakes 80 hits from a small business in the city of Gualeguachu, in which we use technologies such as nuxt, vue, css3, sass, typescript, node and w3schools</p>
      </div>
    </div>

    <div class="w3-third w3-container w3-margin-bottom">
      <a href="https://cer03.vercel.app/" target="_blank">
        <img :src="cer03" alt="Norway" class="w3-hover-opacity imgProjects">
      </a>
      <div class="w3-container w3-white">
        <p><b>Cer03</b></p>
        <p>Together with a group of colleagues we developed an after-sales web application, with the purpose of simplifying the work of sales and product management for small businesses, as well as further empowering large companies, in which we use technologies such as React, redux, vite, css, javascript, node, express and SQL</p>
      </div>
    </div>

    <div class="w3-third w3-container">
      <a href="www.google.com">
        <img :src="pokemon" alt="Norway" class="w3-hover-opacity imgProjects">
      </a>
      <div class="w3-container w3-white">
        <p><b>Pokemon</b></p>
        <p>Web application carried out as an individual project to complete the full stack web programming course. in which I use technologies such as React, redux, Vite, javascript, node, express and SQL</p>
      </div>
    </div>
  </div>
  
  <!-- Second Photo Grid-->
  <!--

    <div class="w3-row-padding">
      <div class="w3-third w3-container w3-margin-bottom">
        <img :src="photo" alt="Norway" style="width:100%" class="w3-hover-opacity">
        <div class="w3-container w3-white">
          <p><b>Lorem Ipsum</b></p>
          <p>Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>
        </div>
      </div>
      <div class="w3-third w3-container w3-margin-bottom">
        <img :src="photo" alt="Norway" style="width:100%" class="w3-hover-opacity">
        <div class="w3-container w3-white">
          <p><b>Lorem Ipsum</b></p>
          <p>Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>
        </div>
      </div>
      <div class="w3-third w3-container">
        <img :src="photo" alt="Norway" style="width:100%" class="w3-hover-opacity">
        <div class="w3-container w3-white">
          <p><b>Lorem Ipsum</b></p>
          <p>Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>
        </div>
      </div>
    </div>
   -->

  <!-- Pagination -->
  <div class="w3-center w3-padding-32">
    <div class="w3-bar">
      <a href="#" class="w3-bar-item w3-button w3-hover-black">«</a>
      <a href="#" class="w3-bar-item w3-black w3-button">1</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">2</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">»</a>
    </div>
  </div>

  <!-- Images of Me -->
  <div class="w3-row-padding w3-padding-16 w3-center" id="about">
      <img :src="jhord" alt="Me"  class="imgAbout">
  </div>

  <div class="w3-container w3-padding-large" style="margin-bottom:32px">
    <h4><b>About Me</b></h4>
    <p>Hello! I'm Gabriel, a passionate fullstack web developer with a deep love for technology and problem solving. I love immersing myself in new challenges and facing them with determination until I find innovative solutions.

My goal is to stand out through my projects, creating impactful solutions that not only solve problems, but also generate a positive impact in the digital world. I am motivated by the idea of ​​reaching more companies with my skills and contributing to the success of their projects.

Every line of code I write is a step forward in my professional journey, and I am committed to continuing to grow and learn in this exciting field. I am always open to new opportunities and challenges that allow me to expand my knowledge and skills.

Join me on this journey as we create extraordinary web experiences together and take your ideas to the next level!</p>
    <hr>

    <!-- Skills -->
    <h4><b>Technical Skills</b></h4>

    <!-- front end -->
    
    <div>
      <h4> Front End </h4>
      <div style="display: flex; justify-content: space-around;"> 
        <div>
          <p class="w3-tooltip">
            <span  
            class="tooltip w3-text w3-tag">HTML</span>
            <img class="img" src="../assets/logos/html5-logo.png" alt="logo HTML">
          </p>
        </div>
        
        <div>
          <p class="w3-tooltip">
            <span
            class=" tooltip w3-text w3-tag">CSS</span>
            <img class="img" src="../assets/logos/css3.png" alt="logo css3">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span  
            class="tooltip w3-text w3-tag">JavaScript</span>
            <img class="img" src="../assets/logos/JavaScript-logo.png" alt="logo JavaScript">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span
            class="tooltip w3-text w3-tag">TypeScript</span>
            <img class="img" src="../assets/logos/Typescript_logo.svg.png" alt="logo TypeScript">
          </p>
        </div>   
        
        <div>
          <p class="w3-tooltip">
            <span  
            class="tooltip w3-text w3-tag">React</span>
            <img class="img" src="../assets/logos/react-logo.svg" alt="logo React">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span  
            class="tooltip w3-text w3-tag">Redux</span>
            <img class="img" src="../assets/logos/redux.svg" alt="logo Redux">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span 
            class="tooltip  w3-text w3-tag">Nuxt</span>
            <img class="img" src="../assets/logos/nuxt-logo.png" alt="logo Nuxt">
          </p>
        </div>   
      </div>
    </div><br/>
    
    <!-- back end -->

    <div>
      <h4> Back End </h4>
      <div style="display: flex; justify-content: space-evenly"> 
        <div>
          <p class="w3-tooltip">
            <span
            class="tooltip w3-text w3-tag">Node.js</span>
            <img class="img" src="../assets/logos/nodejs.png" alt="logo Node.js">
          </p>
        </div>
        
        <div>
          <p class="w3-tooltip">
            <span  
            class="tooltip w3-text w3-tag">Express</span>
            <img class="img" src="../assets/logos/express-logo.png" alt="logo Express">
          </p>
        </div>

      </div>
    </div>

    <!-- others -->
    <div>
      <h4> Others </h4>
      <div style="display: flex; justify-content: space-evenly"> 
        <div>
          <p class="w3-tooltip">
            <span
            class="tooltip w3-text w3-tag">Git</span>
            <img class="img" src="../assets/logos/git-logo.png" alt="logo git.">
          </p>
        </div>
        
        <div>
          <p class="w3-tooltip">
            <span
            class="tooltip w3-text w3-tag">Github</span>
            <img class="img" src="../assets/logos/GitHub-logo.png" alt="logo Githbu">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span 
            class="tooltip w3-text w3-tag">VSC</span>
            <img class="img" src="../assets/logos/VS-logo.png" alt="logo Visual Studio Code">
          </p>
        </div>   


      </div>
    </div>
   
   
    <hr>
    
  </div>
  
  <!-- Contact Section -->
  
  <!--btn-whatsapp-->
  <div class="container-btn">
    <a href="https://wa.me/+543446387033?text=Deseo%20realizar%20un%20proyecto%20web">
      <img class="btnF" src="../assets/logos/whatcuadrado.png" alt="logo whatsapp">
    </a>
  </div>
</template>

<style>

  .container-btn{
    position: fixed;
    z-index: 999;
    border-radius: 20%;
    bottom: 10px;
    right: 10px;
    transition: ease 0.3s;
  }

  .container-btn:hover{
    transform: scale(1);
    transition: 0.3s;
  }

  .btnF{
    width: 100px;
    transition: ease 1s;
  }

  .imgProjects{
    width: 100%;
    max-height: 300px;
  }

  .imgAbout{
    width: 200px;
    border-radius: 10px;
  }

  .img{
  width: 30px;
  }

.tooltip{
  background-color: black;
  color:white;
  text-align: center;
  padding: 2px;
  border-radius: 6px;
  position: absolute;
  bottom: -30px;
  left: 50%;
  transform: translateX(-50%);
}

@media screen and (min-width: 768px) {

.img{
width: 50px;
}

.imgProjects{
    width: 100%;
    max-height: 210px;
  }
.tooltip{
background-color: black;
color:white;
text-align: center;
padding: 2px;
border-radius: 6px;
position: absolute;
bottom: -35px;
left: 50%;
transform: translateX(-50%);
}
}


@media screen and (min-width: 1024px) {

  .img{
  width: 60px;
  }

  .imgAbout{
    width: 300px;
  }

  .tooltip{
  background-color: black;
  color:white;
  text-align: center;
  padding: 2px;
  border-radius: 6px;
  position: absolute;
  bottom: -30px;
  left: 50%;
  transform: translateX(-50%);
}
}

@media screen and (min-width: 1920px) {
  .imgAbout{
    width: 400px;
  }

  .imgProjects{
    width: 100%;
    max-height: 300px;
  }

  .img{
    width: 70px;
  }

  .tooltip{
    background-color: black;
    color:white;
    text-align: center;
    padding: 2px;
    border-radius: 6px;
    position: absolute;
    bottom: -30px;
    left: 50%;
    transform: translateX(-50%);
  }
}
</style>