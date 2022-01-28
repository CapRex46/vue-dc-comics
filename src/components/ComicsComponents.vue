<template>
    <div class="comics">
        
            <div class="comicsinfo" v-for="ComicsTypes in ComicsTypes" :key="ComicsTypes">
                <div class="comicscard">
                    <img :src="ComicsTypes.thumb" alt="">
                    <p>{{ComicsTypes.series}}</p>
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
        width: 100%;
        margin: 0 auto;
        display: flex;
        flex-wrap: wrap;
    } .comicsinfo{
        width: 16%;
        display:flex ;
        justify-content: center;
        margin: 0 auto;
        margin-top: 20px ;
    }
    p {
        color: whitesmoke;
        width: 200px;
        font-size: 15px;
        text-align: left;
        margin-top: 20px;
        margin-bottom: 20px;
    } 
</style>