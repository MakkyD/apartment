<template>
  <div class="">
    <nav class="navbar navbar-expand-lg navbar-light bg-transparent  fixed-top">
  <router-link to="/" class="navbar-brand" ><span style="color: white">AMYLODGE</span></router-link>
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
</template>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
} 
  color: #42b983;
} */
nav{
  background-color: rgba(184, 167, 167, 0.137) !important;
}
nav ul li{
  padding:  0 1rem;
}
li{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  /* font-size: 12px; */
}
nav ul li a{
  color:white !important;
   font-weight: bold;
   font-size: 1.0rem;
   transition: all 0.3s;
   transform: scale(1);
}
span{
  color:rgb(80, 69, 69);
   font-weight: bold;
   font-size: 1.5rem
}
nav ul li a:hover{
color:black !important;
transform: scale(1.2);
border-bottom: 2px solid black;
}
</style>
<style scoped>

</style>
