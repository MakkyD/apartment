<template>
    <div class="RoomsPage">
            <div class="container">
                <app-header2></app-header2>
            </div>
       <div class="container Rooms" style="margin-top:100px">
            <div class="" style="text-align:left">
                   <h1 class="RoomHeading">Choose The Best Rooms And Make Reservations</h1>
               </div>
           <div class="Room1">  
            <div class="row">
                <div class="col-sm-6 col-md-12 col-lg-6">
                    <img src="assets/images/presidential-suite-photo.png" class="img-fluid">
                </div>
                <div class="col-sm-6 col-md-12 col-lg-6" id="roomDescType" >
                    <div>
                        <h1 style="text-align:center">Presidential Suite</h1>
                   
                    <div class="Room-description">
                        <p>spacious, Bright and airy. This Rooom Has Beautiful View Of The Ocean. </p>
                        <span><b>You also get:</b></span>

                        <div>
                            <p>Free Spa Sessions</p>
                            <p>Gim access</p>
                            <p>Complementary Champagne</p>
                        </div>

                            <router-link to="Booking"><button type="button" class="btn btn-dark" id="btn">Book For N200,000</button></router-link>
                    </div>
                    </div>
     
                </div> 
            </div>
            </div>

            <div class="row content" id="desktop-view" style="margin-top:10rem">
                <div class="col-sm-6 col-md-12 col-lg-6 " id="roomDescType2" >
                    <div class="Room-type">
                        <h1>Executive Suite</h1>
                    </div>
                    <div class="Room-description1">
                        <p>spacious, Bright and airy. This Rooom Has Beautiful View Of The Ocean. </p>
                        <span><b>You also get:</b></span>

                    
                            <p>Free Spa Sessions</p>
                            <p>Gim access</p>
                            <p>Complementary Champagne</p>
                        

                            <button type="button" class="btn btn-dark" id="btn"> Book For N200,000</button>
                    </div>
     
                </div>
                 <div class="col-sm-6 col-md-12 col-lg-6 Room-image" >

                    <img src="assets/images/executiveSuites.png" style="width:100%" class="img-fluid" >
                </div>
            </div>

            <div class="row content" id="mobile-view" >
                <div class="col-sm-6 Room-image" >
                    <img src="assets/images/executiveSuites.png" style="width:100%" class="img-fluid">
                </div>
                <div class="col-sm-6 " id="roomDescType2">
                    <div class="Room-type">
                        <h1>Executive Suite</h1>
                    </div>
                    <div class="Room-description1">
                        <p>spacious, Bright and airy. This Rooom Has Beautiful View Of The Ocean. </p>
                        <span><b>You also get:</b></span>

                    
                            <p>Free Spa Sessions</p>
                            <p>Gim access</p>
                            <p>Complementary Champagne</p>
                        

                            <button type="button" class="btn btn-dark" id="btn"> Book For N200,000</button>
                    </div>
     
                </div>
            </div>

             <div class="row content" style="margin-bottom:20px; margin-top:10rem">
                <div class="col-sm-6 col-md-12 col-lg-6" >
                    <img src="assets/images/standard-suite-photo.png" class="img-fluid">
                </div>
                <div class="col-sm-6 col-md-12 col-lg-6" id="roomDescType">
                    <div class="Room-type">
                        <h1>Standard Suite</h1>
                    </div>
                
                    <div class="Room-description">
                        <p>spacious, Bright and airy. This Rooom Has Beautiful View Of The Ocean. </p>
                        <span><b>You also get:</b></span>

                        
                            <p>Free Spa Sessions</p>
                            <p>Gim access</p>
                            <p>Complementary Champagne</p>
                        

                            <button type="button" class="btn btn-dark" id="btn" style=""> Book For N200,000</button>
                    </div>
     
                </div> 
            </div>
            <!-- <div class="Room1"> 
                <div>
                    <h3>Rooms</h3>
                    <img src="assets/images/presidential-suite-photo.png">
                </div>
                <div class="Des-header">
                    <h1 style="text-align:center">Presidential Suite</h1>
                    <div class="Room-description1">
                        <p>spacious, Bright and airy. This Rooom Has Beautiful View Of The Ocean. </p>
                        <span><b>You also get:</b></span>

                            
                                <p>Free Spa Sessions</p>
                                <p>Gim access</p>
                                <p>Complementary Champagne</p>
                            

                                <button type="button" class="btn btn-dark" id="btn" style=""> Book For N200,000</button>
                    </div>
                </div>
            </div> -->

            <div class="SeeBut">
                <router-link to="SeeMoreButton"><button type="submit" class="btn btn-primary">See More ></button></router-link>
            </div>
        </div>
        <app-footer></app-footer>
    </div>
</template>


<style scoped>
.RoomsPage{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.Room-description{
    border: solid white 1px;
    background-color: white;
    border-radius: 3px;
    padding: 40px 40px 40px 40px;
    box-shadow: 0px 0px 5px #00000036;
     position: absolute;
    left: -70px;
    /* width:100%;  */
    }
    .Des-header{
        margin-top:20%
    }
     #mobile-view{
        display: none;
    }
    .Room-description1{
    border: solid white 1px;
    background-color: white;
    border-radius: 5px;
    padding: 40px 40px 40px 40px;
    box-shadow: 0px 0px 5px #00000036;
    position: absolute;
    /* margin-right: -70px; */
    z-index:1;
    right: -10%;
    /* width:50% */
    }
    #roomDescType{
        margin-top: 90px;
        /* transition: all 0.3s;
        transform: scale(1);  */
        
    }
    #roomDescType2{
        margin-top: 30px
    }
    .SeeBut{
        margin:5%
    }
    /* .Room-image{
    position: absolute;
    margin-left: -50px 
    } */
    
    .Room-type{
        text-align:center;
    }

    #btn{
        width:100%;
        background-color:orangered;
        border-radius:8px !important;
        border-color:orangered
    }
    .content{
        margin-top:100px;
    }
    .executiveImage{
    /* width:300% */
    }
    .SeeBut{
    text-align: center;
    margin: 10rem 0rem 2rem 0rem
    
    }
    .SeeBut .btn{
        padding:5px;
        background-color: orangered;
        border-color:orangered;
        border-radius: 5px
    }
   @media only screen and (min-width: 320px) and (max-width:575px) {
       /* *{
           margin: 0;
       } */
       .Room-description{
           position: relative;
           left:auto
       }
       .Room-description1{
           position: relative;
           z-index:1;
            right: auto;
       }
       #mobile-view{
           display: block;
       }
       #desktop-view{
           display: none;
       }
        #roomDescType{
        margin-top: 50px;
        }
        .Rooms{
            text-align: center;
        }
        .SeeBut{
        text-align: center;
        margin: 4rem 0rem 2rem 0rem
    
    }
   }

   @media (min-width: 575px) and (max-width:768px) {
       .Room-description{
           position: relative;
           left:auto
       }
       .Room-description1{
           position: relative;
           z-index:1;
            right: auto;
       }
       #mobile-view{
           display: block;
       }
       #desktop-view{
           display: none;
       }
        #roomDescType{
        margin-top: 70px;
        }
        .Rooms{
            text-align: center;
        }
        .Room-image{
            max-width:100%
        }
        #roomDescType2{
            max-width:100%;
        }
        .RoomHeading{
            text-align: center;
        }
        .SeeBut{
            text-align: center;
            margin: 3rem 0rem 3rem 0rem
    
    }
   }
</style>
    
 <script>



import Header2 from '@/components/Header2.vue'
import footer from '@/components/Footer.vue'
export default {
    components: {
        'app-header2': Header2,
        'app-footer': footer
    }
}

</script>

