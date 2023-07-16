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
            <div class="footer-right-main">
                <div>
                    <h3>
                        DC COMICS  
                    </h3>
                    <div>
                        <a href="#">
                            Characters
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Comics
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Movie
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Tv
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Games
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            videos
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            News
                        </a> 
                    </div>
                    <h3>
                        SHOP
                    </h3>
                    <div>
                        <a href="#">
                            Shop DC
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Shop DC Collectibles
                        </a> 
                    </div>

                </div>
                <div>
                    <h3>
                        DC   
                    </h3>
                    <div>
                        <a href="#">
                            Terms of use
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Privacy policy (News)
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Ad Choices
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Avertising 
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Jobs
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Subscriptions
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Talent workshop
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            CPSC Certificate 
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Ratings
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                           Shop help
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            Contact us
                        </a> 
                    </div>

                </div>
                <div>
                    <h3>
                        SITE   
                    </h3>
                    <div>
                        <a href="#">
                            DC
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            MAD magazine
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            DC Kids
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            DC Universe 
                        </a> 
                    </div>
                    <div>
                        <a href="#">
                            DC Power Visa 
                        </a> 
                    </div>

                </div>
            </div>
            <div class="footer-left-main">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>


    <div class="footer-bottom">
        <div class="container-footer-bottom">
            <div class="footer-right-main" >
                <button>
                    SING-UP NOW
                </button>
            </div>

            <div>
                <span class="footer-left-main">
                    <a href="#">
                        FOLLOW US
                    </a>
                </span>
            </div>
        </div>
    </div>

</footer>

</template>


<style lang="scss" scoped>
// FOOTER TOP
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

// FOOTER MAIN

.footer-main{
    height: 350px;
    background-image: url(../assets/img/footer-bg.jpg);
    .container-footer-main{
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        .footer-right-main{
            width: 40%;
            display: flex;

            h3{
                color: white;
            }
            div{
                padding:0px 20px 4px 0px;
            }
            div  div a{
                color: rgb(175, 175, 175);
               
                font-size: 0.9em;
                text-decoration: none;

            };
            div > div a:hover{
                text-decoration: underline
            }
        };
        .footer-left-main{
            img{
                position: relative;
                left: 100px;
                bottom: 70px;
                height: 500px;
            }

        }
    };
};

// FOOTER BOTTOM

.footer-bottom{
    height: 150px;
    background-color: #303030;
    z-index: 3;
    position: relative;
    .container-footer-bottom{
        width: 100%;
        .footer-right-main{
            width: 40%;
        }
        .footer-left-main{
            width: 60%;
        }
    }
    
}

</style>