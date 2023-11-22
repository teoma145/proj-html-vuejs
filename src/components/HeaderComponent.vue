<template>
    <div class="header-bg position-relative ">
        <div class="d-flex justify-content-between ">
            <div>
            <img src="../assets/style/images/author-logo-round.png" alt="" class="logomy ">
            </div>
            <div>
                <ul class="d-flex text-white fs-2 flex-wrap">
                    <li>Home</li>
                    <li>Altro</li>
                    <li>Altro</li>
                </ul>
            </div>
        </div>
        <div class="myheadertitle d-flex ">
            <div class="myheaderleft d-flex align-items-center justify-content-center ">
                <div class="ms-1 mt-5">
                    <h1 class="colorh1">Damon Vaugh</h1>
                    <h2 class="text-white">Best-Selling Author And The Most <br>Influential PublicIntellectual In <br>The Western World Right Now.</h2>
                    <p class="fs-2 text-secondary">-The New York Times</p>
                </div>
            </div>
        </div>
        <div class="bg-white card-header">
                <div class="d-flex pt-4 ps-4 pe-4 flex-wrap">
                    <img src="../assets/style/images/book-widget.png" alt="">
                    <div>
                        <h3>Latest book Release</h3>
                        <p>D. VAUGHN AUTOBIOGRAPHY</p>
                        <p>Donec fringilla nunc eu turpis<br> dignissim, at euismod sapien<br> tincidunt. Maecenas eleifend congue cursus.</p>
                    </div>
                </div>
                <div class="d-flex justify-content-around  ps-5 pe-5 mb-4">
                    <button>Buy on amazon</button>
                    <button>Buy on App store</button>
                </div>
                
            </div>
    </div>
</template>

<script>
export default {
    name:'HeaderComponent',
    data () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
.header-bg{
    background-image: url(../assets/style/images/footer-3.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top;
    height:900px
}
.logomy{
    width: 140px;
}
ul{
    margin-right: 20px;
    list-style-type: none;
}
li{
    margin-left: 30px;
}
.myheaderleft{
    
    height: 700px;
    width: 70%;
    
    
    
}
.colorh1{
    color:#f4b429;
    font-size: 3em;
}
h2{
    font-size: 3em;
}
.card-header{
    position: absolute;
    bottom: -2px;
    right: 0;
}
@media (max-width: 768px) {
    .card-header {
        position: static;
    }
}
</style>