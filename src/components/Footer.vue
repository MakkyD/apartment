<template>
    <div class="footer" >
        <div class="" >
            <div class="footer1" >
                <div  style="margin-top:40px">
                    <h2>AMYLODGE</h2>
                    <p>2020 Amylodge. All rights reserved</p>
                    <div class="row icons" style="width:50%">
                        <div class="col-4">
                            <img src="assets/images/inst1.png" style="width: 25px">
                        </div>
                        <div class="col-4">
                            <img src="assets/images/tw2.png" style="width:35px">
                        </div>
                        <div class="col-4">
                            <img src="assets/images/fb1.png" style="width: 35px">
                        </div>
                    </div>
                </div>
                <div style="margin-top:40px">
                    <h2> Company</h2>
                    <p>About</p>
                    <p>Terms And Conditions</p>
                    <p>Privacy Policy</p>
                </div>
                <div style="margin-top:40px">
                    <h2> Contact</h2>
                    <p>amakaibiam@gmail.com</p>
                    <p>+2348140159223</p>
                    <p>Lagos, Nigeria</p>
                </div>
                
            </div>
        </div>
    </div>
</template>

<style scoped>
.footer{
margin-top:10px;
}
.footer1{
    display:grid;
    grid-template-columns: 1fr 1fr 1fr;
}

@media(max-width:567px){
    .footer1{
        grid-template-columns: 1fr;
        /* text-align: center; */
    }
    .icons{
        justify-content: center;
    }
}
@media (min-width:567px) and (max-width: 768px) {
    .footer1{
        /* margin:0rem 3rem 0rem 3rem; */
    }
}
</style>