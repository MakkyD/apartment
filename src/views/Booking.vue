<template>
    <div>
        <app-header></app-header>
        <!-- <div class="Form  justify-content-center" style="overflow:hidden" >
            <div >
            <form>
                <div>
                    <h1 style="text-align:center; color">Book A Room</h1>
                </div>
               
                <div class="row">
                    <label for="name" class="col-sm-2 col-form-label">Name</label>
                    <div class="col">
                    <input type="text" class="form-control" placeholder="First name">
                    </div>
                    <div class="col">
                    <input type="text" class="form-control" placeholder="Last name">
                    </div>
                </div>
            <div class="form-group row">
                <label for="inputEmail3" class="col-sm-2 col-form-label">Email</label>
                <div class="col-sm-10">
                <input type="email" class="form-control" id="inputEmail3" placeholder="Email">
                </div>
            </div>
                <div class="form-group row">
                    <label for="inputEmail3" class="col-sm-2 col-form-label">Phone Number</label>
                    <div class="col-sm-10">
                    <input type="number" class="form-control" id="inputEmail3" placeholder="phone">
                    </div>
                </div>
               <div class="form-group row">
                    <label for="inputEmail3" class="col-sm-2 col-form-label">Date From</label>
                    <div class="col">
                    <input type="date" class="form-control" id="inputEmail3" placeholder="">
                    </div>
                     <div class="col">
                        <input type="time" class="form-control" id="inputEmail3" placeholder="">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="inputEmail3" class="col-sm-2 col-form-label">Date to</label>
                    <div class="col">
                    <input type="date" class="form-control" id="inputEmail3" placeholder="">
                    </div>
                     <div class="col">
                        <input type="time" class="form-control" id="inputEmail3" placeholder="">
                    </div>
                </div>
                <div class="form-group row">
                    <label for="inputEmail3" class="col-sm-2 col-form-label">No of people</label>
                    <div class="col-sm-10">
                    <input type="number" class="form-control" id="inputEmail3" placeholder="">
                    </div>
                </div>
                
                <div class="form-group row">
                    <label for="inputEmail3" class="col-sm-2 col-form-label">Comment</label>
                    <div class="col-sm-10">
                    <textarea name="" id="" cols="30" rows="5" class="form-control"></textarea>
                    
                    </div>
                </div>
                <div>
                    <button type="submit" class="btn btn-secondary ">Book Now</button>
                </div>
                
            </form>
            </div>
            <div >
                <img src="/assets/images/q.png" style="width:100%; height:100%;">
            </div>
            </div> -->
            <div class=" desktopView">
                <div class="row">
                    <div class="col-sm-4 card shadow p-4" style="box-shadow: 0px 0px 5px #00000036; padding:top:20rem">
                        <form >
                            <h4>Book A Room</h4>
                                    <!-- <input type="text" name="" id="" placeholder="Name" style="margin-bottom: 20px; width:527px"><br> -->
                                <div class="form-grp">
                                    <!-- <label>Name</label> -->
                                    <input type="text" id="name" class="form-control" placeholder="Name" style="margin-bottom: 20px">
                                </div>
                                <div class="form-grp">
                                    <!-- <label>Name</label> -->
                                    <input type="text" id="name" class="form-control" placeholder="Email" style="margin-bottom:20px">
                                </div>
                                    <!-- <input type="text" name="" id="" placeholder="Name" style="margin-bottom: 20px; width:527px"><br> -->
                                    <textarea name="" placeholder="Type Message" cols="72" rows="5" class="form-control" ></textarea>
                                    <button type="submit" style="color:white; margin:30px 0px 10px 0px; width:100%" class="btn btn-dark form-group">Submit</button>
                            </form>
                    </div>
                    <div class="col-sm-8 BookingImage">
                        <img src="/assets/images/landingPage.png" style="width:100%; height:124.4%;">
                    </div>
                </div>
            </div>

            <div class="mobileView">
                <div class="row">
                    <div class="col-sm-6 card shadow p-4 " style="box-shadow: 0px 0px 5px #00000036; padding:top:20rem">
                        <form >
                            <h4>Book A Room</h4>
                                    <!-- <input type="text" name="" id="" placeholder="Name" style="margin-bottom: 20px; width:527px"><br> -->
                                <div class="form-grp">
                                    <!-- <label>Name</label> -->
                                    <input type="text" id="name" class="form-control" placeholder="Name" style="margin-bottom: 20px">
                                </div>
                                <div class="form-grp">
                                    <!-- <label>Name</label> -->
                                    <input type="text" id="name" class="form-control" placeholder="Email" style="margin-bottom:20px">
                                </div>
                                    <!-- <input type="text" name="" id="" placeholder="Name" style="margin-bottom: 20px; width:527px"><br> -->
                                    <textarea name="" placeholder="Type Message" cols="72" rows="5" class="form-control" ></textarea>
                                    <button type="submit" style="color:white; margin:30px 0px 10px 0px; width:100%" class="btn btn-dark form-group">Submit</button>
                            </form>
                    </div>
                </div>
            </div>




            
        <app-footer></app-footer>
    </div>
</template>

<script>
import Header2 from '@/components/Header2.vue'
import Footer from '@/components/Footer.vue'
export default {
    components:{
    'app-header': Header2,
    'app-footer': Footer 
    }
}
</script>
<style scoped>
/* .Form{
   
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 2rem;
} */
.btn{
 justify-content: center;
}
form{
    /* padding-left: 2rem; */
     margin-top:5rem;
}
.card{
    /* margin:10rem 0rem 0rem 0rem */

}
.desktopView{
    margin-bottom:10rem;
    display: block;
    /* margin-left:4rem */
}.mobileView{
    display: none;
    
}
.BookingImage img{
   /* position: absolute; */
}


@media(max-width:320px){
    /* .Form{
        grid-template-columns: 1fr;
    }
    form{
    padding-left: 1rem;
    padding-right: 1rem;
} */
.desktopView{
    margin-bottom:10rem;
    display: none;
}.mobileView{
    display: block;
}
}
</style>