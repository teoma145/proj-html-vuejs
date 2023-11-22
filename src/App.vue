<template>
  <div>
     <HeaderComponent/>
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
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MeetAutor from './components/MeetAutor.vue';
import BuyAudible from './components/BuyAudible.vue';
import Critics from './components/Critics.vue';
import EventComponent from './components/EventComponent.vue';
import Subscribe from './components/Subscribe.vue';
export default {
  name:'App',
  components:{
   HeaderComponent,
   MeetAutor,
   BuyAudible,
   Critics,
   EventComponent,
   Subscribe,
  },
  data () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>