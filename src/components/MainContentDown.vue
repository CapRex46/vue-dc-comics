<template>
        <div class="infolist">
            <ul>
                <li><img src="..\assets\buy-comics-digital-comics.png" alt=""> DIGITAL COMICS</li>
                <li><img src="..\assets\buy-comics-merchandise.png" alt="">DC MERCHANDISE</li>
                <li><img src="..\assets\buy-comics-subscriptions.png" alt="">SUBSCRIPTIONS</li>
                <li><img src="..\assets\buy-comics-shop-locator.png" alt="">COMIC SHOP LOCATOR</li>
                <li><img src="..\assets\buy-comics-merchandise.png" alt="">DC POWER VISA</li>
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
            height: 200px;
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
            }
        }
</style>