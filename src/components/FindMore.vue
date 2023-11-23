<template>
    <div class="text-center mt-5">
        <h2 class="text-black">Dig A Little Into Damon Vaughn</h2>
        <h3 class="coloraqua fs-5 mt-3">FIND OUT MORE ABOUT THE AUTHOR HIMSELF</h3>
    </div>
    <div class="container">
       <div class="row  justify-content-between ">
         <div class="col-md-3 col-12 findimg overlay mt-5" v-for="(card, index) in FindCard" :key="index" :style="{ 'background-image': 'url(' + card.image + ')' }">
            <div class="d-flex flex-column text-center  justify-content-end  h-100">
                <h3 class="text-white">{{ card.title }}</h3>
                <hr class="text-white">
                <p class="coloryellow">{{ card.description }}</p>
            </div>
            
         </div>
       </div>
    </div>
</template>

<script>

export default {
    name:'Findmore',
    data() {
        

        return {
            FindCard:[
            {
                  image:'./images/box-1.jpg',
                  title:'About Me',
                  description:'Vestibilum ante ipsum primis.',
                },
                {
                  image:'./images/box-3.jpg',
                  title:'My Latest Book',
                  description:'Vestibilum ante ipsum primis.',
                },
                {
                  image:'./images/box-4.jpg',
                  title:'Book Signign',
                  description:'Vestibilum ante ipsum primis.',
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.findimg{
    height: 400px;
    background-size: cover;
    background-position: center;
    transition: transform 0.5s;
    border-radius: 0 0 30px 0;
    overflow: hidden;
    
}
hr{
    width: 20%;
    margin: 0 auto;
}
.findimg:hover {
            transform: scale(1.03); 
        }
</style>