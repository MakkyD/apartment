 <template>
    <div class="Contact">
        <div >
            <app-header2></app-header2>
        </div>
        <div class="container desktopView">
            <div class="row" style="margin: 100px 0px 40px 0px">
                <div class="col-sm-6">
                    <h3 style="margin-bottom:10%">We'd Love To Hear From You</h3>
                    <div class="row">
                        <div class="col-6">
                            <b>Our Address</b>
                            <p>No, 10 Utuks Lane,<br> Off Nwaniba Anua Uyo.</p>
                        </div>
                        <div class="col-6"> 
                            <b>Support</b>
                            <p>amaka@gmail.com<br>+2349091120199</p>
                        </div>
                    </div>
                </div>
                <div class="col-sm-6 card shadow p-4 " style="box-shadow: 0px 0px 5px #00000036;">
                    <form >
                        <h4>Send Us A Message</h4>
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


        <div class="container mobileView">
            <div class="row" style="margin: 100px 0px 40px 0px">
                <div class="col-sm-6 card shadow p-4 " style="box-shadow: 0px 0px 5px #00000036;">
                    <form >
                        <h4>Send Us A Message</h4>
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
                 <div class="col-sm-6 text">
                    <h3 style="margin-bottom:10%">We'd Love To Hear From You</h3>
                    <div class="row">
                        <div class="col-6">
                            <b>Our Address</b>
                            <p>No, 10 Utuks Lane,<br> Off Nwaniba Anua Uyo.</p>
                        </div>
                        <div class="col-6"> 
                            <b>Support</b>
                            <p>amaka@gmail.com<br>+2349091120199</p>
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
    components: {
        'app-header2': Header2,
        'app-footer': footer
    }
}
</script>
<style scoped>
.Contact{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.desktopView{
    display:block
}
.mobileView{
    display:none
}
@media (max-width: 320px){
    .card{
        max-width: 100%;
    }
.desktopView{
    display:none
}
.mobileView{
    display:block;
}
.text{
    margin-top:4rem
}
.card{
    margin-top:1rem
}
}
@media (min-width: 321px) and (max-width:576px){
.desktopView{
    display:none
}
.mobileView{
    display:block;
}
.text{
    margin-top:5rem
}
.card{
    margin-top:1rem
}
}
</style>