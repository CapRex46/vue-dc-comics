<template>
    <div class="backfooter">
        <div class="buttons"> 
            <div class="signup">
                <h3>SIGN UP NOW!</h3>
            </div>
            <div class="follow">
                <h3>FOLLOW US</h3>
                <img src="../assets/footer-facebook.png" alt="">
                <img src="../assets/footer-periscope.png" alt="">
                <img src="../assets/footer-twitter.png" alt="">
                <img src="../assets/footer-youtube.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    .backfooter{
        width: 100%;
        height: 200px;
        background: black;
    } .buttons {
        width: 1400px;
        margin: 0 auto;
    } .signup {
        color: white;
        float: left;
        padding-top: 80px;
    } .follow {
        color: #0282F9;
        float: right;
        padding-top: 80px;
    }
</style>