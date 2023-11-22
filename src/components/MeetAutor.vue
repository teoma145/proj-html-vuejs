<template>
    <div class="mt-5 text-center container">
      <h1>More About Damon Vaughn</h1>
      <p>Damon Vaughn is a professor of psychology at the University of Toronto, a clinical psychologist 
        and the author of the multi-million copy bestseller “The story of my life.”
      </p>
      <button class="mb-5 mt-2">Meet the autor</button>
      <div class="d-flex flex-wrap justify-content-between mymarg">
        <div v-for="(itemsites, index) in sellingsites" :key="index">
          <img :src="itemsites" alt="item">
        </div>
         
      </div>
    </div>
</template>

<script>
export default {
    name:'MeetAutor',
    data() {
        

        return {
          sellingsites:[
            './images/audible.png',
            './images/ebay.png',
            './images/kindle.png',
            './images/logotan.png',
          ]
        }
    }
}
</script>

<style lang="scss" scoped>
p{
  font-size: 2em;
}
img{
  width: 240px;
  
}
.mymarg{
  margin-top: 130px;
}
</style>