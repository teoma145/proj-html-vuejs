<template>
  <div>
     <HeaderComponent/>
  </div>
  <div>
    <MeetAutor/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MeetAutor from './components/MeetAutor.vue';
export default {
  name:'App',
  components:{
   HeaderComponent,
   MeetAutor,
  },
  data () {
    

    return {}
  }
}
</script>

<style lang="scss" scoped>

</style>