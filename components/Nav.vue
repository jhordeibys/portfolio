<script lang="ts" setup>
import jhord from "@/assets/img/jhordeibys.jpeg";

const { showNav } = useNavBar();

const handleCloseNav = () => {
  showNav.value = false;
}

</script>

<template>
  <!-- Sidebar/menu -->
  <nav
    class="w3-sidebar w3-collapse w3-white w3-animate-left nav"
    :class="{'show-nav': showNav}"
  >
    <br>
    <div class="w3-container">
      <a
        href="#"
        class="w3-hide-large w3-right w3-jumbo w3-padding w3-hover-grey"
        title="close menu"
        @click="handleCloseNav()"
      >
        <i class="fa-solid fa-xmark fa-xs"></i>
      </a>

      <img :src="jhord" class="w3-round img-width"><br><br>
      <h4><b>PORTFOLIO</b></h4>
      <p class="w3-text-grey">Template by W3.CSS</p>
    </div>
    <div class="w3-bar-block">
      <a href="#portfolio" class="w3-bar-item w3-button w3-padding w3-text-teal"><i class="fa fa-th-large fa-fw w3-margin-right"></i>PORTFOLIO</a> 
      <a href="#about" class="w3-bar-item w3-button w3-padding"><i class="fa fa-user fa-fw w3-margin-right"></i>ABOUT</a> 
      <a href="#contact" class="w3-bar-item w3-button w3-padding"><i class="fa fa-envelope fa-fw w3-margin-right"></i>CONTACT</a>
    </div>
    <!-- icons social media-->
    
    <div class="w3-panel w3-large">
      <a href="https://www.google.com"><i class="fa-brands fa-facebook w3-hover-opacity"></i></a>


      
      <i class="fa-brands fa-instagram w3-hover-opacity"></i>
      <i class="fa-brands fa-x-twitter w3-hover-opacity"></i>
      <i class="fa-brands fa-linkedin w3-hover-opacity"></i>
      <i class="fa-brands fa-github w3-hover-opacity"></i>
      <i class="fa-brands fa-gitlab w3-hover-opacity"></i>
    </div>
  </nav>

  <!-- Overlay effect when opening sidebar on small screens -->
  <div
    class="w3-overlay w3-hide-large w3-animate-opacity overlay"
    title="close side menu"
    :class="{'show-overlay': showNav}"
  ></div>
</template>
<style lang="scss">
.nav {
  z-index: 3;
  width: 300px;
}

.img-width {
  width:45%;
}
.overlay {
  cursor: pointer;
}
.show-overlay {
  display: block;
}
.hide-overlay {
  display: none;
}
.show-nav {
  display: block !important;
}
.hide-overlay {
  display: none;
}
</style>