<template>
  <div>
     <HeaderComponent/>
  </div>
  <div>
    <FixedComponent/>
  </div>
  <div>
    <MeetAutor/>
  </div>
  <div>
    <BuyAudible/>
  </div>
  <div>
    <Critics/>
  </div>
  <div>
    <EventComponent/>
  </div>
  <div>
    <Subscribe/>
  </div>
  <div>
    <FindMore/>
  </div>
  <div>
    <ArticlesComponent/>
  </div>
  <div>
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MeetAutor from './components/MeetAutor.vue';
import BuyAudible from './components/BuyAudible.vue';
import Critics from './components/Critics.vue';
import EventComponent from './components/EventComponent.vue';
import Subscribe from './components/Subscribe.vue';
import FindMore from './components/FindMore.vue';
import ArticlesComponent from './components/ArticlesComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import FixedComponent from './components/FixedComponent.vue';
export default {
  name:'App',
  components:{
   HeaderComponent,
   MeetAutor,
   BuyAudible,
   Critics,
   EventComponent,
   Subscribe,
   FindMore,
   ArticlesComponent,
   FooterComponent,
   FixedComponent,
  },
  data () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>