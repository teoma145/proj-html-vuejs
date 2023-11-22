<template>
    <div class="mt-5 container  text-center">
       <h2>Upcoming Events</h2>
       <h3 class="fs-5 coloryellow">Meet The Author In Person</h3>
       <div class="d-flex justify-content-between flex-wrap">
            <div class="col-12 col-md-3" v-for="(item, index) in mycard" :key="index">
                <CardComponent :image="item.image" :title="item.title" :description="item.description"/>
            </div>
        </div>
    </div>
</template>

<script>
import CardComponent from './CardComponent.vue';
export default {
    name:'EventComponent',
    components:{
        CardComponent,
    },
    data () {
        

        return {
            mycard:[
                {
                  image:'./images/event3.jpg',
                  title:'Chicago Book Signing',
                  description:'Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a nulla.',
                },
                {
                  image:'./images/event1.jpg',
                  title:'Meet & Greet With Amanda',
                  description:'Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Praesent sapien massa, convallis a pellentesque nec, egestas.',
                },
                {
                  image:'./images/event2.jpg',
                  title:'Open Book: Dialogues',
                  description:'Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a nulla.',
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>

</style>