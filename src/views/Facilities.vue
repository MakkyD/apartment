<template>
  <div class="about">
    <div>
      <app-header2></app-header2>
    </div>
    <!-- <div class="container" id="Facilities">
      <h1 style="margin: 10px 0px 10px 0px">Facilities</h1>
    
    <div class="row">
      <div class="col">
        <img src="assets/images/chelsea.png" class="imageSize">
      </div>
      <div class="col">
        <img src="assets/images/jared.png" class="imageSize">
      </div>
      <div class="col">
        <img src="assets/images/house2.jpg"  class="imageSize">
      </div>
    </div>
    
    <div class="row" style="margin:40px 0 40px 0px">
      <div class="col">
        <img src="assets/images/humphrey.png"  class="imageSize">
      </div>
      <div class="col">
        <img src="assets/images/q.png"  class="imageSize">
      </div>
      <div class="col">
        <img src="assets/images/robert.png"  class="imageSize">
      </div>
    </div>
    </div> -->
<div class="outterContainer">
  <div class="container innerContainer">
    <h1 style="margin: 10px 0px 10px 0px">Facilities</h1>
    <div class="row">
      <div class="col-sm-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front"  style="background: url(assets/images/pool2.jpg) center center/cover">
            <!-- <img src="img_avatar.png" alt="Avatar" style="width:300px;height:300px;"> -->
            <h1 class="text-shadow">POOL</h1>
          </div>
        </div>
      </div>

      <div class="col-sm-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front"  style="background: url(assets/images/jared.png) center center/cover">
            <!-- <img src="img_avatar.png" alt="Avatar" style="width:300px;height:300px;"> -->
            <h1 class="text-shadow">SPA</h1>
          </div>
        </div>
      </div>
      <div class="col-sm-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front"  style="background: url(assets/images/colorful.png) center center/cover">
            <!-- <img src="img_avatar.png" alt="Avatar" style="width:300px;height:300px;"> -->
            <h1 class="text-shadow">ART GALLERY</h1>
          </div>
        </div>
</div>
    </div>
  </div>
  <div class="container">
    <div class="row ">
      <div class="col-sm-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front"  style="background: url(assets/images/humphrey.png) center center/cover">
            <!-- <img src="img_avatar.png" alt="Avatar" style="width:300px;height:300px;"> -->
            <h1 class="text-shadow">GYM</h1>
          </div>
        </div>
    </div>

      <div class="col-sm-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front"  style="background: url(assets/images/tennis.jpg) center center/cover">
            <!-- <img src="img_avatar.png" alt="Avatar" style="width:300px;height:300px;"> -->
            <h1 class="text-shadow">TENNIS COURT</h1>
          </div>
        </div>
      </div>

      <div class="col-sm-4 flip-card">
        <div class="flip-card-inner">
          <div class="flip-card-front"  style="background: url(assets/images/robert.png) center center/cover">
            <!-- <img src="img_avatar.png" alt="Avatar" style="width:300px;height:300px;"> -->
            <h1 class="text-shadow">GOLF COURT</h1>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>



    <app-footer></app-footer>
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
*{
}
#Facilities{
  margin-top: 8%
}
/* .imageSize{
  width:100%
} */
.front{
  background:no-repeat;
  height: 15rem;
}
.flip{
  margin-top:10%;
  position: relative;
  
}
.text-shadow{
  color: white;
  text-align: center;
  padding-top: 10rem;
  font-weight: 1000;
}

.flip-card {
  background-color: transparent;
  width: 100%;
  height: 250px;
  /* border: 1px solid #f1f1f1; */
  perspective: 1000px; /* Remove this if you don't want the 3D effect */
  margin-bottom: 3rem
}

.innerContainer{
  padding-top: 7rem
}
.about{
  /* background-color: black; */
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

/* This container is needed to position the front and back side */
.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  /* transition: transform 0.8s; */
  /* transform-style: preserve-3d; */
}

/* Do an horizontal flip when you move the mouse over the flip box container */
.flip-card:hover .flip-card-inner {
  /* transform: rotateY(180deg); */
}

/* Position the front and back side */
.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden; /* Safari */
  backface-visibility: hidden;
}

/* Style the front side (fallback if image is missing) */
.flip-card-front {
  background-color: #bbb;
  color: black;
}


@media (max-width: 320px) {
 
}
@media (min-width: 321px) and (max-width: 375px) {
 
@media (min-width: 376px) and (max-width: 425px) {

}
}
</style>
