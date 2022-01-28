<template>
    <div class="comics">
        <div class="comicsinfo" v-for="ComicsTypes in ComicsTypes" :key="ComicsTypes">
            <div class="comicscard">
                <img :src="ComicsTypes.thumb" alt="">
                <h3>{{ComicsTypes.type}}</h3>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props:{ 
        ComicsTypes : Array
    }
}
</script>

<style lang="scss" scoped>  
    .comics{
        background: #1C1C1C;
        height: 600px;
    } .comicsinfo{
        width: 1200px;
        margin: 0 auto;
        display: flex;
        flex-flow: wrap;
    } .comicscard {
        width: 25%;
    } h3 {
        color: whitesmoke;
    }
</style>