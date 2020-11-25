<template>
<div>
   <div class="container">
    <nav class="navbar navbar-expand-lg navbar-light bg-white fixed-top">
  <router-link to="/" class="navbar-brand"><span>AMYLODGE</span></router-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active">
        <router-link to="About" class="nav-link" > About<span class="sr-only">(current)</span></router-link>
      </li>
      <li class="nav-item">
        <router-link to="Rooms" class="nav-link" >Rooms</router-link>
      </li>
       <li class="nav-item">
        <router-link to="Facilities" class="nav-link" >Facilities</router-link>
      </li>
      <li class="nav-item">
        <router-link to="Services" class="nav-link" >Services</router-link>
      </li>
       <li class="nav-item">
        <router-link to="Contact" class="nav-link" >Contact</router-link>
      </li>
    </ul>
  </div>
</nav>
  </div>
</div>
   

</template>


<style scoped>
nav{
 box-shadow: 0px 0px 5px #00000036;
  
   
}
nav ul li a{
  color: black !important;
   font-weight: bold;
   font-size: 1.0rem;
}
nav ul li{
   padding: 0 1rem;
}
span{
  color:black !important;
   font-weight: bold;
   font-size: 1.5rem;
}
.nav-con{
 
}
</style>