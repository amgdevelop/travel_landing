<template>
    <div class="container-fluid m-0 p-0">
        <div id="home-page" class="full-height p-4">
            <div class="container pt-3">
                <div class="row pb-5">
                    <div class="col-lg-6 pt-4 my-auto">
                        <div class="text-center mb-3 d-block d-lg-none">
                            <h1 class="display-3">{{title}}</h1>
                            <h3>Find the World</h3>
                        </div>
                        <div class="d-flex justify-content-center">

                        <img id="iphone-img" src="../assets/travelTreasuryiPhone.png" alt="iphone image" class="img-fluid ">
                        </div>
                    </div>
                    <div class="col-lg-6 pt-4 mt-5">
                        <div class="text-center mb-3 d-none d-lg-block mt-5">
                            <h1 class="display-3">{{title}}</h1>
                            <h3>Find the World</h3>
                        </div>

                        <div class="border p-3 p-md-5 bg-white rounded shadow">
                            <h2 class="text-center">Coming Soon</h2>
                            <form >
                                <div class="form-group">
                                    <label for="emailSignup" class="m-3">
                                        Reserve your account now, we´ll contact you when it´s live
                                    </label>
                                    <input type="text" id="emailSignup" placeholder="Enter Email" class="form-control">
                                    <small id="emailHelp" class="form-text text-muted d-block text-center mb-2">
                                        We´ll never share your email adress
                                    </small>
                                    <div class="d-flex justify-content-center">

                                        <button type="submit" class="btn btn-success mt-3">Join Waiting List</button>
                                    </div>
                                </div>
                            </form>
                        </div>

                        <div id="available" class="p-2">
                            <h4 class="text-center mb-2 mt-3 text-light">
                                Available On
                            </h4>
                            <div class="row">
                                <div class="col my-auto">
                                 <img src="../assets/download_apple.png" alt="apple download" class="float-right img-fluid app_store_img">   
                                </div>
                                <div class="col my-auto">
                                 <img src="../assets/download_google.png" alt="android download" class="float-left img-fluid app_store_img">   
                                </div>

                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>


<!--  -->




        <div id="about" class="bg-light p-3 p-md-5  p-4">
            <div class="row">
                <div class="col-lg d-flex flex-column">
                    <!-- Made with freepick perfect from www.flaticon.com -->
                    <img src="../assets/icons/app.svg" alt="mobile-icon" height="120" class="m-4">
                    <h5 class="ml-md-4 mr-md-4">
                        Plan your next adventure by setting a daily spending budget.
                        We make it easy to break your expenses down by category,
                        giving you more time to plan the important things!
                    </h5>
                </div>
                
                <div class="col-lg d-flex flex-column">
                    <img src="../assets/icons/piggy-bank.svg" alt="mobile-icon" height="120" class="m-4">
                    <h5 class="ml-md-4 mr-md-4">
                        Use the app to track how much money you´ve saved towards your trips total budgeted goal.
                        Know exactly  how much more you need to save,
                        and how much time you have left to save.
                    </h5>
                </div>

                <div class="col-lg d-flex flex-column">
                    <img src="../assets/icons/passport.svg" alt="mobile-icon" height="120" class="m-4">
                    <h5 class="ml-md-4 mr-md-4">
                        When the day of your trip comes, have the peace of mind that you planned out your expenses. Never worry about money on a trip again.‹
                    </h5>
                </div>
            </div>


        </div>

    
    <!--  -->



        <div id="contact" class="bg-info p-4">
            <div class="row justify-content-center mt-3 mb-3">
                <div class="col-lg-4">
                    <h2>Have Any Questions?</h2>
                    <p>Contact us by filling out the information below</p>

                    <form>
                        <div class="form-group text-left">
                            <input type="email" class="form-control" placeholder="Enter your Email">
                            <textarea class="form-control mt-3"
                             placeholder="Entenr Your Message"
                             rows="5"></textarea>
                        </div>
                    </form>
                </div>
            </div>

        </div>
        <div id="footer" class="bg-primary p-4">


        </div>
    </div>
</template>
<script>
export default {
    name: 'HomePage',
    data(){
        return {
            title: 'Travel Treasury'
        }
    }
}
</script>
<style scoped>

#home-page {
    background-color: #92D2F2;
    background: url('../assets/bg_mt.jpg') no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
}

#iphone-img {
    max-height: 80vh;
}

</style>