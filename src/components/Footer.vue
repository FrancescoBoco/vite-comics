<script>

</script>

<template>
<footer>
    <div class="footer-top">
        <div>
            <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <div>
                    DIGITAL COMICS
                </div>
            </div>
            <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <div>
                    DC MERCHANDISE 
                </div>
            </div>
            <div>
                <img src="../assets/img/buy-comics-subscriptions.png"  alt="">
                <div>
                    SUBSCRIPTION
                </div>
            </div>
            <div>
                <img src="../assets/img/buy-comics-shop-locator.png"  alt="">
                <div>
                   COMIC SHOP LOCATOR
                </div>
            </div>
            <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <div>
                    DC POWER VISA
                </div>
            </div>
           
        </div>
    </div>


    <div class="footer-main">
        <div class="container-footer-main">
            
        </div>
    </div>


    <div class="footer-bottom">
        <div class="container-footer-bottom">


        </div>
    </div>

</footer>

</template>


<style lang="scss" scoped>
.footer-top{
    height: 200px;
    background-color: #3382F1;
    > div{
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-around;
        height: 100%;
        > div {
            height: 100%;
            align-items: center;
            display: flex;
            img{
                height: 70px;
            }
            > div{
                padding: 10px;
                color: white;
                font-size: 0.9em;
            }
        }
    }
}
</style>