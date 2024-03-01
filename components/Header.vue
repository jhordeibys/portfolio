<script setup lang="ts">
import photo from "@/assets/img/avatar_g2.jpg";
import jhord from "@/assets/img/jhordeibys.jpeg";

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

    <div class="w3-container">
    <h1><b>Jhordeibys Gabriel Da Silva Raaz</b></h1>
    </div>

  </header>
  
  <!-- First Photo Grid-->
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
  
  <!-- Second Photo Grid-->
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
  <div class="w3-row-padding w3-padding-16" id="about">
    <div class="w3-col m6">
      <img :src="photo" alt="Me" style="width:100%">
    </div>
    <div class="w3-col m6">
      <img :src="photo" alt="Me" style="width:100%">
    </div>
  </div>

  <div class="w3-container w3-padding-large" style="margin-bottom:32px">
    <h4><b>About Me</b></h4>
    <p>Just me, myself and I, exploring the universe of unknownment. I have a heart of love and an interest of lorem ipsum and mauris neque quam blog. I want to share my world with you. Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla. Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>
    <hr>

    <!-- Skills -->
    <h4><b>Technical Skills</b></h4>

    <!-- front end -->
    
    <div>
      <h4> Front End </h4>
      <div style="display: flex; justify-content: space-around;"> 
        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">HTML</span>
            <img class="img" src="../assets/logos/html5-logo.png" alt="logo HTML">
          </p>
        </div>
        
        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">CSS</span>
            <img class="img" src="../assets/logos/css3.png" alt="logo css3">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">JavaScript</span>
            <img class="img" src="../assets/logos/JavaScript-logo.png" alt="logo JavaScript">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">TypeScript</span>
            <img class="img" src="../assets/logos/Typescript_logo.svg.png" alt="logo TypeScript">
          </p>
        </div>   
        
        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">React</span>
            <img class="img" src="../assets/logos/react-logo.svg" alt="logo React">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">Redux</span>
            <img class="img" src="../assets/logos/redux.svg" alt="logo Redux">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">Nuxt</span>
            <img class="img" src="../assets/logos/nuxt-logo.png" alt="logo Nuxt">
          </p>
        </div>   


      </div>
    </div>
    
    <!-- back end -->

    <div>
      <h4> Back End </h4>
      <div style="display: flex; justify-content: space-evenly"> 
        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">Node.js</span>
            <img class="img" src="../assets/logos/node-logo.svg" alt="logo Node.js">
          </p>
        </div>
        
        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">Express</span>
            <img class="img" src="../assets/logos/express-logo.png" alt="logo Express">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">JavaScript</span>
            <img class="img" src="../assets/logos/JavaScript-logo.png" alt="logo JavaScript">
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
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">Git</span>
            <img class="img" src="../assets/logos/git-logo.png" alt="logo git.">
          </p>
        </div>
        
        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">Github</span>
            <img class="img" src="../assets/logos/GitHub-logo.png" alt="logo Githbu">
          </p>
        </div>   

        <div>
          <p class="w3-tooltip">
            <span style="position:absolute; left:0; bottom:18px" 
            class="w3-text w3-tag w3-white">Visual Studio Code</span>
            <img class="img" src="../assets/logos/VS-logo.png" alt="logo Visual Studio Code">
          </p>
        </div>   


      </div>
    </div>
   
   
    <hr>
    
  </div>
  
  <!-- Contact Section -->
  <div class="w3-container w3-padding-large w3-grey">
    <h4 id="contact"><b>Contact Me</b></h4>
    <div class="w3-row-padding w3-center w3-padding-24" style="margin:0 -16px">
      <div class="w3-third w3-dark-grey">
        <p><i class="fa fa-envelope w3-xxlarge w3-text-light-grey"></i></p>
        <p>gdasilvadev@gmail.com</p>
      </div>
      <div class="w3-third w3-teal">
        <p><i class="fa fa-map-marker w3-xxlarge w3-text-light-grey"></i></p>
        <p>Gualeguaychu, Entre Rios, Argentina</p>
      </div>
      <div class="w3-third w3-dark-grey">
        <p><i class="fa fa-phone w3-xxlarge w3-text-light-grey"></i></p>
        <p>+543446387033</p>
      </div>
    </div>
    <hr class="w3-opacity">
    <form action="/action_page.php" target="_blank">
      <div class="w3-section">
        <label>Name</label>
        <input class="w3-input w3-border" type="text" name="Name">
      </div>
      <div class="w3-section">
        <label>Email</label>
        <input class="w3-input w3-border" type="text" name="Email">
      </div>
      <div class="w3-section">
        <label>Message</label>
        <input class="w3-input w3-border" type="text" name="Message">
      </div>
      <button type="submit" class="w3-button w3-black w3-margin-bottom"><i class="fa fa-paper-plane w3-margin-right"></i>Send Message</button>
    </form>
  </div>

</template>

<style>
.img{
  width: 50px;
}
</style>