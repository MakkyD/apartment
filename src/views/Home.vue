<template>
 <div >
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <div id="bg-image">
      
      <div class="">
        
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <app-header></app-header>
            <!-- <ol class="carousel-indicators">
              <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
              <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
            </ol> -->
        <div class="carousel-inner">
          <div class="carousel-item active">
              <img class="d-block w-100" src="assets/images/landingpage.png" alt="First slide" style="height:80vh">
            <div class="carousel-caption d-none d-md-block">
                <h1 style="color:orangered">AMY'S LOUNGE</h1>
                <p>Palace Hotel. More Than Just Luxury.</p>
                <router-link to="Rooms"><button class="btn btn-light button">Explore</button></router-link>
              
            </div>
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="assets/images/executiveSuites.png" alt="Second slide" style="height:80vh">
            <div class="carousel-caption d-none d-md-block">
                <h1 style="color: orangered">AMY'S LOUNGE</h1>
                <p>Palace Hotel. More Than Just Luxury.</p>
                <router-link to="Rooms"><button class="btn btn-light button">Explore</button></router-link>
              
            </div>
          </div>
          <div class="carousel-item">
            <img class="d-block w-100" src="assets/images/standard-suite-photo.png" alt="Third slide" style="height:80vh">
            <div class="carousel-caption d-none d-md-block">
                <h1 style="color:orangered">AMY'S LOUNGE</h1>
                <p>Palace Hotel. More Than Just Luxury.</p>
                <router-link to="Rooms"><button class="btn btn-light button">Explore</button></router-link>
              
            </div>
          </div>
        </div>
          <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
    </div>

      <div class=" container Date">
        <div class="">
        <div class="grid">
          <div class="grid1">
            <div class="Dateinput">
              <label for="Date In" >Date In</label>
            </div>
            <div>
              <input type="text">
            </div>
          </div>
          <div class="grid1">
            <div  class="Dateinput">
              <label for="Date Out">Date Out</label>
            </div>
            <div>
              <input type="text">
            </div>
          </div>
          <div class="grid1">
            <button type="button">Book Now</button>
          </div>
        </div>
      </div>
      </div>
       </div>
    </div>


    <div class="Testimonial">
      <div>
        <h1 style="color:orangered; padding-top:3rem">TESTIMONIAL</h1>
      </div>
      <div class="container row TestimonialContainer">
        <div class="col-sm-4">
            <img src="assets/images/jared.png" class="TestimonialImage img-responsive">
          <p class="text" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat pariatur ex eos
             assumenda et velit similique tenetur iste quia deleniti minus impedit dolorem 
           dignissimos est sint, maxime, rerum ipsam itaque.</p>
        </div>
        <div class="col-sm-4" >
            <img src="assets/images/massage-2.jpg" class="TestimonialImage img-responsive" id="testImage">
          <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat pariatur ex eos
             assumenda et velit similique tenetur iste quia deleniti minus impedit dolorem 
            dignissimos est sint, maxime, rerum ipsam itaque.</p>
        </div>
        <div class="col-sm-4">
          <img src="assets/images/massage-2.jpg" class="TestimonialImage img-responsive" id="testImage">
          <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat pariatur ex eos
             assumenda et velit similique tenetur iste quia deleniti minus impedit dolorem 
            dignissimos est sint, maxime, rerum ipsam itaque.</p>
        </div>
      </div>
    </div>
    <app-footer></app-footer>
  </div>
  
  
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

// export default {
//   name: 'Home',
//   components: {
//     HelloWorld
//   }
// }
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue"
export default{
  components:{
    'app-header': Header,
    'app-footer': Footer
  }
  
}
</script>
<style scoped>
 /* #bg-image{
  color:white;
  background-image: url("/assets/images/humphrey.png");
  background-size: cover;
  background-repeat: no-repeat;
  height: 100vh;
} */

.d-block{
  filter: brightness(20%)
}
.button{
  background-color: transparent;
  color:white;
  border-radius:0px;
  width: 20%;
  /* padding: 1.5%; */
  border: solid white;
  font-size: larger;
  margin-bottom: 5rem;
  margin-top: 2rem;
  padding: 1rem;
}
.button:hover{
  background-color: white;
  color:rgb(8, 7, 71);
}
.bookNow{
  background-color: rgb(255, 30, 0);
  width: 70%;
}
.Date{
  background-color: white;
  margin-top: -4.5rem;
  position: relative;
  box-shadow: 0px 0px 5px #00000036;
  padding: 1rem 0rem 2rem 0rem;
  width:50rem
}
 
.grid{
  display:grid;
  grid-template-columns: 1fr 1fr 1fr;
  margin-left: 3rem;
  margin-right: 3rem;
  text-align: center;
  
}
.grid1 input{
  width: 80%;
  border-color:orangered;
  height:3.5rem
}
.grid1 button{
  width: 80%;
  margin-top: 2rem;
  border-color:orangered;
  height: 3.5rem;
  background-color:orangered;
  color:white
}
.Testimonial{
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0), rgba(0, 0, 0, 1.657)), url(/assets/images/executiveSuites.png); 
  background-color: grey;
  height:35.140rem; 
  margin-top: 5%;
  background-size: cover;
  background-attachment: fixed;
}
.TestimonialImage{
  border-radius:50%;
  width:40%;
  height: 60%;
  margin-bottom:2.5rem
  /* margin-right:10rem; */
  /* margin-left: 11rem; */
}
.TestimonialContainer{
   margin-left: 5rem;
   padding-top:3rem;
   
}
.Testimonial{
  text-align:center;
  margin-bottom:10rem
}

.text{
  color:white;
}

@media (min-width: 320px) and (max-width:576px) {
  .Date{
  background-color: white;
  margin-top: -4.5rem;
  position: relative;
  box-shadow: 0px 0px 5px #00000036;
  padding: 1rem 0rem 2rem 0rem;
  width:20rem
}
.grid{
  display: block;
  text-align: center;
}
.grid1 input{
  width: 90%;
  border-color:orangered;
  height:3.5rem
}
.grid1 button{
  width: 90%;
  margin-top: 2rem;
  border-color:orangered;
  height: 3.5rem;
  background-color:orangered;
  color:white
}
.TestimonialContainer{
   margin-left: 0rem;
   padding-top:2rem;
}

.TestimonialImage{
  border-radius:50%;
  width:20%;
  height: 25%;
  margin-top:0rem;
  margin-bottom:1rem
  /* margin-right:10rem; */
  /* margin-left: 11rem; */
}
#testImage{
margin-top:2rem
}
.Testimonial{
  background-image: linear-gradient(180deg, rgba(0, 0, 0, 0), rgba(0, 0, 0, 1.657)), url(/assets/images/executiveSuites.png); 
  background-color: grey;
  height:170vh; 
  margin-top: 5%;
  background-size: cover;
  background-attachment: fixed;
}
}

@media (min-width: 576px) and (max-width: 768px) {
 .TestimonialContainer{
   margin-left:2rem;
   padding-top:3rem;
   
}
.TestimonialImage{
  border-radius:50%;
  width:50%;
  height: 30%;
  margin-top:0rem;
  margin-bottom:1rem
  /* margin-right:10rem; */
  /* margin-left: 11rem; */
}
}

@media (min-width: 768px) and (max-width:991.98px) {
  .TestimonialContainer{
   margin-left:2rem;
   padding-top:3rem;
   
}
}
@media (max-width:1024px) {
  .TestimonialContainer{
   /* margin-left:2rem; */
   padding-top:3rem;
   
}
}
</style>
