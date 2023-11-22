<template>
    <div class="shadow-on-hover">
        <img :src="image" :alt="title"  class="mt-5">
        <div class="mt-3">
            <h3 class="card-title mb-4">{{ title }}</h3>
            <p>{{ description }}</p>
        </div>
    </div>
</template>

<script>
export default {
    name:'CardComponent',
    props: [
        'image',
        'title',
        'description',
    ],
    data () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
img{
    width:100%;
}
.shadow-on-hover {
  transition: box-shadow 0.3s;
}

.shadow-on-hover:hover {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3); /* Puoi personalizzare i valori dell'ombra a tuo piacimento */
}
</style>