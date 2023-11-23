<template>
    <div class="fixediv">
        <div class="bg-white mb-3 div-fix">
            <span class="fontmy">Prebuilts</span>
        </div>
        <div class="bg-white div-fix">
            <span class="fs-6 text-info">$</span><span class="fs-5 text-info">45</span><br><span class="fontmy">On sale</span>
        </div>
    </div>
</template>

<script>
export default {
    name:'FixedComponent',
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>
.fixediv{
    position: fixed;
    right:20px;
    top:300px
}
.div-fix{
    width: 60px;
    height: 60px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}
.fontmy{
    font-size: 0.7em;
    padding: 5px;
    
}
</style>