<template>
    <navBar />

    <!-- banner -->
    <div class="container-fluid content">
        <div class="row bg-warning py-4 justify-content-center ">
            <div class="col-md-6 col-11 px-4 gap-3 d-flex flex-column justify-content-center text-white ">
                <h1 class="d-block">First i Wanted to be a engineer</h1>
                <p class="d-block">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Velit consectetur
                    perferendis labore
                    numquam tenetur architecto soluta dolor deleniti, natus veritatis.</p>
                <div>
                    <button type="button" class="btn btn-danger btns">Contact Us</button>
                    <button type="button" class="btn btn-outline-light btns">Our Services</button>
                </div>

            </div>
            <div class="col-md-4 mb-4 d-none d-md-block d-flex justify-content-center ">
                <img class="img-fluid" src="@/assets/main.png" alt="Randam img">
            </div>
        </div>

        <!-- 2nd banner -->
        <div class="row py-5 justify-content-center">
            <div class="col-md-5 col-11 px-4 gap-3 d-flex flex-column justify-content-center  ">
                <h1 class="d-block">As an engineer i love to do good work</h1>
                <p class="d-block">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Velit consectetur
                    perferendis labore
                    numquam tenetur architecto soluta dolor deleniti, natus veritatis.</p>
                <div>
                    <button type="button" class="btn btn-warning btns">Contact Us</button>

                </div>

            </div>
            <div class="col-md-5 mb-4  col-11  d-flex justify-content-center ">
                <img class="img-fluid" src="@/assets/main-2.jpg" alt="Randam img">
            </div>
        </div>


        <div class="row bg-warning py-5 justify-content-center ">
            <div class="col-md-3 col-11 p-4 gap-3 d-flex flex-column justify-content-center text-white text-center">
                <i class="bi bi-hearts d-block " style="font-size: 15vh;"></i>
                <h1 class="fw-bold">+34793</h1>
                <h1 class="fw-bold">Happy Client</h1>
            </div>
            <div class="col-md-3 col-11 p-4 gap-3 d-flex flex-column justify-content-center text-white text-center">
                <i class="bi bi-fire d-block " style="font-size: 15vh;"></i>
                <h1 class="fw-bold">+3.0</h1>
                <h1 class="fw-bold">Rating</h1>
            </div>
            <div class="col-md-3 col-11 p-4 gap-3 d-flex flex-column justify-content-center text-white text-center">
                <i class="bi bi-person-workspace d-block " style="font-size: 15vh;"></i>
                <h1 class="fw-bold">+34793</h1>
                <h1 class="fw-bold">Work Done</h1>
            </div>
        </div>
        <!-- blog -->
        <div class="row py-5 justify-content-center">
            <div class="col-12 text-center">
                <h1 class="fw-bolder">Recent Posts</h1>
                <p class="fs-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus <br> quis nesciunt perferendis
                    molestias illum.</p>
            </div>

            <!-- card -->
            <div class="col-md-3 col-11 mb-4">
                <img src="@/assets/blog1.jpg" class="img-fluid" alt="Random Img">
                <div class="arti-detail">
                    <h4 class="arti-title">As a engineer I love to invent different things</h4>
                    <p class="arti-date">MAY 20,2024</p>
                    <p class="arti-desc">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nesciunt, nulla.</p>
                    <p class="arti-link">Read More+</p>
                    
                </div>
            </div>
            <div class="col-md-3 col-11 mb-4">
                <img src="@/assets/blog2.jpg" class="img-fluid" alt="Random Img">
                <div class="arti-detail">
                    <h4 class="arti-title">As a engineer I love to invent different things</h4>
                    <p class="arti-date">MAY 20,2024</p>
                    <p class="arti-desc">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nesciunt, nulla.</p>
                    <p class="arti-link">Read More+</p>
                    
                </div>
            </div>
            <div class="col-md-3 col-11 mb-4">
                <img src="@/assets/blog3.jpg" class="img-fluid" alt="Random Img">
                <div class="arti-detail">
                    <h4 class="arti-title">As a engineer I love to invent different things</h4>
                    <p class="arti-date">MAY 20,2024</p>
                    <p class="arti-desc">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nesciunt, nulla.</p>
                    <p class="arti-link">Read More+</p>
                </div>
            </div>
        </div>

        <!-- footer -->

        <div class="row py-5 footer1  text-white   justify-content-center align-items-">
            <div class="col-md-3 col-11">
                <h1>About</h1>
                <ul class="no-list-style">
                    <li>History</li>
                    <li>Our Team</li>
                    <li>Brand Guidelines</li>
                    <li>Terms&Condition</li>
                    <li>Privacy Policy</li>
                </ul>
            </div>
            <div class="col-md-3 col-11">
                <h1>Services</h1>
                <ul class="no-list-style">
                    <li>How to Order</li>
                    <li>Our Product</li>
                    <li>Order Status</li>
                    <li>Promo</li>
                    <li>Payment Method</li>
                </ul>
            </div>
            <div class="col-md-3 col-11 text-md-end ">
                <h1>Title Here</h1>
                <p>Lorem ipsum dolor sit amet consectetur.</p>
                <form action="">
                    <input class="formSearch" type="text">
                    <button class="formBtn border-0"><i class="bi bi-cursor-fill"></i></button>
                </form>
                <div class="mt-3 " >
                    <i class="bi bi-twitter me-2"></i>
                    <i class="bi bi-instagram me-2"></i>
                    <i class="bi bi-whatsapp me-2"></i>
                    <i class="bi bi-facebook me-2"></i>
                </div>
            </div>
        </div>
        

    </div>



</template>

<!-- script section -->
<script>
import navBar from './navBar.vue';
export default {
    name: "HomePage",
    components: {
        navBar,
    },
}
</script>

<!-- style section -->
<style scoped>



/* for btns */
.btns {
    height: 50px;
    font-size: large;
    margin-right: 10px;
    margin-bottom: 15px;
} 
.arti-detail{
    padding: 15px;
    border: 1px solid rgb(185,185,185);
    border-top: 0px;
}
.arti-date, .arti-link{
    color:#00bec9 ;
}

/* footer */
.footer1{
    background-color: #343434;
}
.formBtn{
    height: 30px;
    width: 40px;
    font-size: large;
    background-color: #ffc107;

}
.formSearch{
    height: 30px;
    
    border: none;
    max-width: 300px;
    position: relative;
    
}
.no-list-style{
    list-style: none;
}
</style>