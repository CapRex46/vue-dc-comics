<template>
        <div class="infolist">
            <ul>
                <li><img src="..\assets\buy-comics-digital-comics.png" alt=""><div class="infotxt"> DIGITAL COMICS</div></li>
                <li><img src="..\assets\buy-comics-merchandise.png" alt=""><div class="infotxt">DC MERCHANDISE</div></li>
                <li><img src="..\assets\buy-comics-subscriptions.png" alt=""><div class="infotxt">SUBSCRIPTIONS</div></li>
                <li><img src="..\assets\buy-comics-shop-locator.png" alt=""><div class="infotxt">COMIC SHOP LOCATOR</div></li>
                <li><img src="..\assets\buy-comics-merchandise.png" alt=""><div class="infotxt">DC POWER VISA</div></li>
            </ul>
        </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scooped>
        .infolist{
            width: 100%;
            height: 250px;
            background: #0282F9;
            
            ul{
                width: 1400px;
                margin: 0 auto;
                list-style: none;
                display: flex;
                justify-content: space-between;
                padding-top: 80px ;
                color: white;

                img{
                    width: 70px;
                    height: 80px;
                } 
                
                li{
                    text-align: center;
                }
                
                .infotxt{
                    margin: 20px;
                }
            }
        }
</style>