<template>
    <header>
        <div class="logo">
            <img src="@/assets/dc-logo.png" alt="">
            <nav>
                    <ul>
                        <li>CHARACTERS</li>
                        <li>COMICS</li>
                        <li>MOVIES</li>
                        <li>TV</li>
                        <li>GAMES</li>
                        <li>COLLECTIBLES</li>
                        <li>VIDEOS</li>
                        <li>FANS</li>
                        <li>NEWS</li>
                        <li>SHOP</li>
                    </ul>
            </nav>

        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scooped>
    header{
        width: 100%;
        text-align: start;
        .logo{
            width: 1400px;
            margin: 0 auto;

            nav {
            float: right;
            display:  flex;
            margin: 0 auto;

            ul{
                list-style: none;
                display: flex;
                justify-content: flex-end;
                margin: 0 auto;

                li{
                    font-size: 20px;
                    padding: 15px;
                    cursor: pointer;

                    &:hover{
                        color: #0282F9;
                        border-bottom:#0282F9 1px solid ;
                    }
                }
            }
        }
        }


    }

</style>