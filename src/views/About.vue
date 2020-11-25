<template>
  <div class="about">
    <div class="nav-con">
       <app-header2></app-header2>
    </div>
   
  <div class="container desktopView" style="margin-top:100px">
    <h1>About Us</h1>
     <div class="row aboutImages">
       <div class="col-sm-4">
          <img src="assets/images/hotelroom2.jpg" class="img1">
       </div>
        <div class="col-sm-4">
          <img src="assets/images/hotelroom3.jpg" class="img2">
       </div>
       <div class="col-sm-4 ">
          <img src="assets/images/hotelroom6.jpg" class="img3">
       </div>
     </div>
     <div class="aboutText">
       <p>
          <span class="app-1 aaps-1">Lorem ipsum dolor sit amet consectetur adipisicing elit. delectus. Illum eaque veritatis, sit eum inventore explicabo adipisci </span>
          <span class="app-1 aaps-1">Eveniet, expedita beatae pariatur perspiciatis consectetur alias repellendus ipsam nulla quaerat quisquam excepturi,  </span>
          <span class="app-1 aaps-1">Eveniet, expedita beatae pariatur perspiciatis consectetur alias repellendus ipsam nulla quaerat quisquam excepturi,</span>
      </p>
    </div>
  </div>

  <div class="container mobileView" style="margin-top:100px">
    <h1>About Us</h1>
    <div class="aboutText">
       <p>
          <span class="app-1 aaps-1">Lorem ipsum dolor sit amet consectetur adipisicing elit. delectus. Illum eaque veritatis, sit eum inventore explicabo adipisci </span>
          <span class="app-1 aaps-1">Eveniet, expedita beatae pariatur perspiciatis consectetur alias repellendus ipsam nulla quaerat quisquam excepturi,  </span>
          <span class="app-1 aaps-1">Eveniet, expedita beatae pariatur perspiciatis consectetur alias repellendus ipsam nulla quaerat quisquam excepturi,</span>
      </p>
    </div>
     <div class="row aboutImages">
       <div class="col-sm-4">
          <img src="assets/images/hotelroom2.jpg" class="img1">
       </div>
        <div class="col-sm-4">
          <img src="assets/images/hotelroom3.jpg" class="img2">
       </div>
       <div class="col-sm-4 ">
          <img src="assets/images/hotelroom6.jpg" class="img3">
       </div>
     </div>
  </div>
  <footer>
    <app-footer></app-footer>
  </footer>
  
  </div>
</template>

<script>
import Header2 from '@/components/Header2.vue'
import footer from '@/components/Footer.vue'
export default {
  components : {
    'app-header2': Header2,
    'app-footer': footer
  }
  
}
</script>

<style scoped>
/* .nav-con{
  box-shadow: grey 1px 1px 1px 1px;
} */
.about{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.img1{
  width:100%;
}
.img2{
  width:100%;
  margin-top:-10%;
  height:43vh
}
.img3{
  width:100%
}
.aboutImages{
  margin: 5rem 0rem 5rem 0rem
}
.aboutText{
  color:grey;
  margin: 0rem 7rem 3rem 7rem
}
.app-1::after{
content:'\a';
white-space:pre;
}
.desktopView{
  display: block;
}
.mobileView{
  display: none;
}

@media (max-width: 320px) {
  .img2{
      width:100%;
      margin-top:1rem;
      height:20vh
}
.img3{
  width:100%;
  margin-top:1rem
}
.aboutText{
  color:grey;
  margin: 0rem 0rem 3rem 0rem;
  text-align: center;
  font-size:1.2rem
}
h1{
  text-align: center;
}
.desktopView{
  display: none;
}
.mobileView{
  display: block;
}
}
@media (min-width: 321px) and (max-width: 576px) {
.desktopView{
  display: none;
}
.mobileView{
    display: block;
}
.img2{
    width:100%;
    margin-top:1rem;
    height:25vh
}
.img3{
  width:100%;
  margin-top:1rem
}
.aboutText{
  color:grey;
  margin: 0rem 3rem 3rem 3rem;
  text-align: center;
  font-size:1.2rem
}
h1{
  text-align: center;
}
}
@media (min-width: 577px) and (max-width: 768px) {
  .img2{
      width:100%;
      margin-top:-1rem;
      height:23vh
}
.aboutText{
  color:grey;
  margin: -1.5rem 2.5rem 3rem 2.5rem;
  text-align: center;
  font-size:1.3rem
}
}
</style>
