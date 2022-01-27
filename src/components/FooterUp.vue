<template>
    <footer>
        <div class="footerlist">
            <h3>DC COMICS</h3>
            <ul>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>            
                <li>lorem</li>
                <li>lorem</li>
                <li>lorem</li>
            </ul>
                <h3>DC COMICS</h3>
            <ul>
                <li>lorem</li>
                <li>lorem</li>

            </ul>
        </div>

    </footer>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scooped>
    footer{
        background: url('../assets/footer-bg.jpg');
        width: 100%;
        height: 500px;
        background-size: cover;
        
        .footerlist{
            width: 1400px;
            margin: 0 auto;
            color: lightgray;
            display: flex;
            justify-content: space-between;
            flex-direction: column;
        } h3 {
            padding-top: 30px;
            padding-bottom: 30px;
        } ul {
            list-style: none;
        }
    }
</style>