<script>

</script>

<template>
<div class="header-empty">

</div>
<div class="container">
   
    <div class="header-components">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <div class="elements" >
                <ul>
                    <li>
                       <a href="#">
                        CHARACTERS
                       </a>
                    </li>
                    <li>
                        <a href="#">
                            COMICS
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            MUVIES
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            TV
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            GAMES
                        </a>
                    </li>

                    <li>
                        <a href="#">
                            COLLECTIBLES
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            VIDEOS
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            FANS
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            NEWS
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            SHOP
                        </a>
                    </li>
                    
                </ul>
        </div>
    </div>
</div>

</template>


<style lang="scss" scoped>
.header-empty{
    height: 80px;
    background: rgb(0,0,0);
    background: linear-gradient(0deg, rgba(0,0,0,1) 0%, rgba(85,85,85,1) 100%);
}
.container{
    height: 100px;
    max-width: 1200px;
    margin: 0 auto;
}

.header-components{
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
    background-color: white;
    .logo{
        height: 80px;
        img{
            height: 100%;
        }
    }
}


.elements{
    display: flex;
    width: 60%;
}

ul{
    display: flex;
    justify-content: space-around;
    width: 100%;
    height: 100%;
    
}

.elements ul li,
.elements ul li a
{
    list-style: none;
    text-decoration: none;
    color: black;
    font-size: 0.9em;
    font-weight: bold;

    &:hover,
    &.active{
        color: #3382F1;
        border-bottom: 2px solid #3382F1;
        transition: 0.3s;
        
    }
}





</style>