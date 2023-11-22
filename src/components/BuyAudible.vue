<template>
    <div class="bg-myimg mt-5  mb-4">
        <div class="container ">
            <div class="d-flex row">
                <div class="col-12 col-md-6">
                    <img src="../assets/style/images/audible-app-2x.png" alt="">
                </div>
                <div class=" col-12 col-md-6 text-myimg text-center ">
                    <h2 class="text-white">New Audiobook</h2>
                    <h3>NO TIME TO READ? NO PROBLEM. LISTEN TO IT</h3>
                    <p>Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas eleifend congue cursus.</p>
                    <button>Buy this on audible</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'BuyAudible',
    data() {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
.bg-myimg{
    background-image: url(../assets/style/images/banner.jpg);
    background-size: cover;
    background-repeat: no-repeat;
}
img{
    width:70%;
    margin-top:15%;
    margin-left:15%;
}
h3{
    color:#f4b429;
    font-size:1.2em;
}
.text-myimg{
    margin-top: 20%;
}
</style>