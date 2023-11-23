<template>
    <div class="mb-5 marginart">
        <div class="container-md mb-3">
        <div class="row d-flex">
            <div class="col-12 col-md-7 ">
                <h2>Recent Articles</h2>
                <h4 class="text-info fs-5 mb-3">READ THE LATEST ENTRIES</h4>
                <div class="bcgrimg">
                </div>
                <div class="ms-2 mt-3">
                    <a href="" class="text-black fs-4 text-decoration-none">20 Creativity Tips</a>
                    <p>By admin|October 24th, 2019|Categories: Event, Tips & Tricks</p>
                    <p>Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet.</p>
                </div>
            </div>
            <div class="col-12 col-md-5 mt-3 d-flex flex-column  align-items-center ">
                <div class="text-end">
                    <a href="" class="text-end text-decoration-none text-white borderbutton-3  mt-4">All Articles</a>
                </div>
                <div class=" wdimg">
                    <img src="../assets/style/images/thumb-13-2x-320x202.jpg" alt="">
                </div>
                <div class="wdimg pt-5">
                    <img src="../assets/style/images/thumb-08-2x-320x202.jpg" alt="">
                </div>
                <div>

                </div>
                </div>
        </div>
    </div>
    </div>
</template>

<script>
export default {
    name:'ArticlesComponent',
    data () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
img{
    width: 100%;
}
.bcgrimg{
    
    background-image: url('../assets/style/images/20-Tips.jpg');
    background-size: cover;
    background-position: center;
    border-radius: 0 0 30px 0;
    overflow: hidden;
    height: 500px;
    padding: 90px;
}
.wdimg{
    width: 280px;
    
    margin-top: 70px;
}
.marginart{
    margin-top: 200px;
}
</style>