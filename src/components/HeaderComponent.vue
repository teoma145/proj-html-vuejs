<template>
    <div class="header-bg position-relative ">
        <div class="d-flex justify-content-between ">
            <div>
            <img src="../assets/style/images/author-logo-round.png" alt="" class="logomy ">
            </div>
            <div class="d-flex text-white fs-2 flex-wrap">
                <div v-for="(headeritem, index) in Headeritems" :key="index" class="headeritem">
                    <div class="orangehover"></div>
                    <div v-if="headeritem === 'Shop'">
                    <div class="shop-title">Shop<i class="fa-solid fa-chevron-down" style="color: #ffffff;"></i></div>
                    
                    <div class="additional-div">
                        <div class="text-nowrap hover-color-additional d-flex align-items-center justify-content-center  ">
                            <span>simple product</span>
                        </div>
                        <div class="text-nowrap hover-color-additional d-flex align-items-center justify-content-center">
                            <span>variable product</span>
                        </div>
                    </div>
                    </div>
                    <span v-else-if="index !== Headeritems.length - 1" class="Hoveritem">{{ headeritem }}</span>
                    <span v-else v-html="headeritem" class="Hoveritem">
                    
                    </span>
                </div>
                
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
                <div class="d-flex justify-content-around  ps-5 pe-5 mb-4 text-center">
                    <div class="borderbutton"><i class="fa-brands fa-amazon" style="color: #000000;"></i>Buy on Amazon</div>
                    <div class="borderbutton"><i class="fa-brands fa-apple" style="color: #030303;"></i>Buy on App store</div>
                </div>
                
            </div>
    </div>
</template>

<script>
export default {
    name:'HeaderComponent',
    data () {
        

        return {
            Headeritems:[
            'Home',
            'About Me',
            'Testimonials',
            'My Blog',
            'Meetups',
            'Shop',
            'Contact Me',
            '<i class="fa-solid fa-cart-shopping" style="color: #edeff2;"></i>'

            ]
        }
    }
}
</script>

<style lang="scss" scoped>

.header-bg{
    background-image: url(../assets/style/images/hero-07-2x.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: top;
    height:900px
}
.additional-div{
 display: none;
 position: absolute;
 top: 30px; 
 left: 0;
 background-color: black;
 z-index: 1; 
}
.headeritem:hover .additional-div {
    display: block;
  }
.logomy{
    width: 140px;
    margin-left: 65px;
}
.hover-color-additional{
    width: 200px;
    height: 40px;
    text-align: center;

}
.hover-color-additional:hover {
        background-color: #49a987; 
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
.headeritem{
    position: relative;
    margin-right: 50px;
    margin-top: 35px;
    font-size: 0.55em;
    &:hover {
    .orangehover {
      display: block;
    }
  }
    
   }
.Hoveritem:hover{
    color:#f4b429;
    cursor: pointer;
}
.orangehover{
    background-color: #f4b429;
    height: 4px;
    position: absolute;
    top: -35px; 
    width: 100%;
    display: none;
}
</style>