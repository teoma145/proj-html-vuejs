<template>
    <div class="myimgbg mt-5 d-flex justify-content-center align-items-center">
        <div class="mt-5">
            <h2 class="text-white mt-5">Subscribe To My Newsletter</h2>
            <h3 class="coloryellow fs-5 mt-3">BE NOTIFIED ABOUT BOOK SIGNING TOUR DATES</h3>
            <div class="d-flex justify-content-center mt-3 flex-wrap">
                <input type="email" placeholder="insert your e-mail" class="p-2">
                <div class="ms-3 borderbutton-2 text-white text-center">Subscribe</div>
            </div>
            <p class="mt-3">Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt.</p>
        </div>
       
    </div>
</template>

<script>

export default {
    name:'Subscribe',
    data () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
.myimgbg{
    background-image: url(../assets/style/images/banner-2.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    height:400px
}
</style>