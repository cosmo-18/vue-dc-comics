<template>
<footer>
    <div class="cont_pre_foot">
    <div class="bg_img">
        <div>
            <ul class="ul">
                <h3>DC COMICS</h3>
                <li>
                    <a href="">Characters</a>
                </li>
                <li>
                    <a href="">Comics</a>
                </li>
                <li>
                    <a href=""> Movies</a>
                </li>
                <li>
                    <a href="">TV</a>
                </li>
                <li>
                    <a href="">Games</a>
                 </li>
                <li>
                    <a href="">Videos</a>
                </li>
                <li>
                    <a href=""> News</a>
                </li>
                </ul>
            <div class="shop">
            <h3>SHOP</h3>
            <ul class="ul">
                <li>
                    <a href="">
                        Shop DC
                    </a>
                </li>
                <li>
                    <a href="">
                        Shop DC collectibles
                    </a>
                </li>
            </ul>
            </div>
        </div>
        <div class="flex_ul">
               <ul class="ul">
                <h3>DC</h3>
                   <li>
                    <a href="">Terms of Use</a>
                   </li>
                   <li>
                    <a href="">Privacy Policy (new)</a>
                   </li>
                   <li>
                    <a href="">Ad Choies</a>
                   </li>
                   <li>
                    <a href="">Advertisings</a>
                   </li>
                   <li>
                    <a href="">Jobs</a>
                   </li>
                   <li>
                    <a href="">Subscriptions</a>
                   </li>
                   <li>
                    <a href="">Talent Workshop</a>
                   </li>
                   <li>
                    <a href="">CPSC Certificate</a>
                   </li>
                   <li>
                    <a href="">Ratings</a>
                   </li>
                   <li>
                    <a href="">Shop Help</a>
                   </li>
                   <li>
                    <a href="">Contact US</a>
                   </li>
                </ul>
                <div>
                    <ul class="ul">
                        <h3>SITES</h3>
                        <li>
                            <a href="">DC</a>
                        </li>
                        <li>
                            <a href="">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="">DC kids</a>
                        </li>
                        <li>
                            <a href="">DC Universe</a>
                        </li>
                        <li>
                            <a href="">DC Power Visa</a>
                        </li>
                    </ul>
                </div>
                        <div>
            <img class="img_bg" src="../assets/img/dc-logo-bg.png" alt="">
        </div>
            </div>
    </div>
    </div>
    <div class="foot_cont">
    <div class="container">
        <div>
            <button>SIGN-UP-NOW</button>
        </div>
        <div class="flex_foot">
            <h4>FOLLOW US</h4>
            <a href="">
                <img class="icon" src="../assets/img/footer-facebook.png" alt="">
            </a>
            <a href="">
                <img class="icon" src="../assets/img/footer-periscope.png" alt="">
            </a>
            <a href="">
                <img class="icon" src="../assets/img/footer-pinterest.png" alt="">
            </a>
            <a href="">
                <img class="icon" src="../assets/img/footer-twitter.png" alt="">
            </a>
            <a href="">
                <img class="icon" src="../assets/img/footer-youtube.png" alt="">
            </a>   
        </div>
    </div>
    </div>
</footer>

</template>

<script>

export default {

  name: 'FooterComp'

}
</script>

<style lang="scss">
    .cont_pre_foot{
        padding: 20px 0px;
        color: white;
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        

            .bg_img{
                width: 70%;
                display: flex;
                margin: auto;
         }   
    }

    .img_bg{
        
        margin-left: 60px;
        width: 60%;
        z-index: 1000;

    }

    .flex_ul{
        display: flex;
        flex-direction: row;
    }



    li{
        font-size: 12px;
        padding-right: 10px;
        padding: 5px 0;
        list-style: none;

        a{
            color: gray;
            text-decoration: none;
        }
    }
        .ul{
            margin-right: 35px;
            padding: 14px 0px;
        }
        
.foot_cont{

    background-color: rgb(48, 47, 47);
    padding: 20px 0px;

    .container{
    width: 70%;

    display: flex;
    align-items: center;
    margin: auto;
    justify-content: space-between;
    
    }
    h4{
    color:#0282f9;
    margin-right: 20px;
    }

    button{
    background-color: rgb(48, 47, 47) ;
    color: white;
    padding: 10px;
    border: 2px solid  #0282f9;
    border-radius: 4px;
    }

}

.flex_foot{
    display: flex;
    align-items: center;

    .icon{
    margin-right: 10px;
    width: 65%;

}

}
</style>