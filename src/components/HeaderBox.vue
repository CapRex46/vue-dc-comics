<template>
    <header>
        <div class="logo">
            <img src="@/assets/dc-logo.png" alt="">
            <nav>
                    <ul>
                        <li v-for="nav in nav" :key="nav"> 
                            {{nav.label}}
                        </li>
                    </ul>
            </nav>

        </div>
    </header>
</template>

<script>

export default {
    props: {
        nav: Array
    }
}
</script>

<style lang="scss" scooped>
    header{
        width: 100%;
        height: 150px;
        text-align: start;
        .logo{
            width: 1400px;
            margin: 0 auto;
            padding: 20px;

            nav {
            float: right;
            display:  flex;
            margin: 0 auto;
            padding-top: 25px ;

            ul{
                list-style: none;
                display: flex;
                justify-content: flex-end;
                margin: 0 auto;
                height: 100px;

                li{
                    font-size: 20px;
                    padding: 15px;
                    cursor: pointer;
                    transition: .5s;

                    &:hover{
                        color: #0282F9;
                        border-bottom:#0282F9 1px solid ;
                        transition: .5s;
                    }
                }
            }
        }
        }


    }

</style>