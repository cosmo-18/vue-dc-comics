<template>
<main>
    <div class="jumbo">
    </div>
        <div class="black">
          <div class="contain">
            <span class="label">CURRENT SERIES</span>
            <div class="comic">
                <FumettoComp v-for="(elem, index) in Comics" :key="index" :datiComic="elem"/>
            </div>
          </div>
        </div>
     <div></div>
    <div class="clrBlue">
        <div class="cont">
            <div class="container">
                <img class="img_3" src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div  class="container">
                <img class="img" src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDAISE</span>
            </div>
            <div  class="container">
                <img class="img_2" src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div  class="container">
                <img class="img" src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="container">
                <img class="img" src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC POWER VISA</span>
            </div>
        </div>
    </div>
</main>
</template>


<script>

import FumettoComp from '../components/FumettoComp.vue'


export default {

  name: 'MainComp',
  components: { 
    
    FumettoComp

  },

    data(){
    return{
      
      Comics : [
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
    "price": "$19.99",
    "series": "Action Comics",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
    "price": "$3.99",
    "series": "American Vampire 1976",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
    "price": "$16.99",
    "series": "Aquaman",
    "type": "graphic novel"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
    "price": "$2.99",
    "series": "Batgirl",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$3.99",
    "series": "Batman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
    "price": "$2.99",
    "series": "Batman Beyond",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
    "price": "$3.99",
    "series": "Batman/Superman",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
    "price": "$4.99",
    "series": "Batman/Superman Annual",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
    "price": "$5.99",
    "series": "Batman: The Joker War Zone",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
    "price": "$6.99",
    "series": "Batman: Three Jokers",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
    "price": "$4.99",
    "series": "Batman: White Knight Presents: Harley Quinn",
    "type": "comic book"
  },
  {
    "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
    "price": "$16.99",
    "series": "Catwoman",
    "type": "graphic novel"
  }
]
    }
  },

}
</script>

<style lang="scss">

.jumbo{
    background-image: url(../assets/img/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    height: 300px;

}

    .black{
        background-color: black;

    }

    .comic{
        flex-wrap: wrap;
         display: flex;

    }

    .fumetto{
        width: calc(100%/4);
        padding: 20px;
        

    }

.bord{
    width: 70%;

    h5{
        color: white;
        padding: 20px 0px;
        font-size: 12px;
    }
    
}
    
    .fum{
      width: 100%;
      padding: 40px 0px;
    }
    
    

.contain{

  width: 70%;
  margin: auto;

.label{
      text-align: center;
      background-color: #0282f9;
      padding: 15px;
      border-radius: 5px;
      position: relative;
      top: -10px;
      color: white;
    }

}

.clrBlue{
    display: flex;
    background-color:  #0282f9;
    padding: 40px 0px;

    .cont{
        display: flex;
        align-items: center;
        justify-content: space-around;
        margin: auto;
        color: white;
        width: 70%;
        font-size: 12px;
        gap: 50px;
    }

    .container{
        display: flex;
        width: 100%;
        align-items: center;
        
    }

    .img{
        width: 30%;
        margin-right: 10px;
    }

    .img_2{
        width: 20%;
        margin-right: 10px;
    }
    .img_3{
        width: 25%;
        margin-right: 10px;
    }
}
</style>