<template>
  <div>

    <nuxt />
    <section class="contact">
  <div class="contact-main">
    <div class="contact-top">
      <div class="contact-left">
        <div class="contact2">
          <img class="logo" src="~assets/image/logo.svg" alt="">
          </div>
          <div class="contact4">
            <p>お問い合わせはこちらから</p>
            <div class="contact-item">
              <div class="contact-center">
                <p>CONTACT</p>
                <img src="~assets/image/right-arrow-s-white.svg" alt="">
              </div>
            </div>
            <p>シュクレイのウェブサイトからお問い合わせください</p>
            <p>メープルマニアではオフィシャルSNSで<br>最新の情報をお届けしています。</p>   
          </div>
 </div>
          <div class="contact-right">
            <div class="contact1">
              <h3>TOP</h3>
              <img class="scroll" src="~assets/image/scrolltop-arrow-brown.svg" alt="">
            </div>
            <div class="contact3">
              <img class="contact-image1" src="~assets/image/half-bw-01.jpg" alt="">
            </div>
          </div>
    </div>
  
  <div class="contact-bottom">
   <div class="sns">
    <img class="insta" src="~assets/image/instagram-brown.svg" alt="">
    <img class="facebook" src="~assets/image/facebook-brown.svg" alt="">
    <img class="twitter" src="~assets/image/twitter-brown.svg" alt="">
  </div>
    <div class="contact5">
      <p>運営会社</p>
      <p>・</p>
      <p>採用情報</p>
    </div>
  </div>
  </div>
</section>

<section class="contact-res">
  <div class="contact-main">
    <div class="contact1">
      <h3>TOP</h3>
      <img class="scroll" src="~assets/image/scrolltop-arrow-brown.svg" alt="">
    </div>
      <div class="contact2">
         <img class="logo" src="~assets/image/logo.svg" alt="">
         </div>
        <div class="contact3">
          <img class="contact-image1" src="~assets/image/half-bw-01.jpg" alt="">
        </div>
   <div class="contact4">
    <p>お問い合わせはこちらから</p>
    <div class="contact-item">
      <div class="contact-center">
        <p>CONTACT</p>
        <img src="~assets/image/right-arrow-s-white.svg" alt="">
      </div>
    </div>
    <p>シュクレイのウェブサイトからお問い合わせください</p>
    <p>メープルマニアではオフィシャルSNSで<br>最新の情報をお届けしています。</p>
    <div class="sns">
      <img class="insta" src="~assets/image/instagram-brown.svg" alt="">
      <img class="facebook" src="~assets/image/facebook-brown.svg" alt="">
      <img class="twitter" src="~assets/image/twitter-brown.svg" alt="">
    </div>
  </div>
    <div class="contact5">
      <p>運営会社</p>
      <p>・</p>
      <p>採用情報</p>
    </div>
  </div>
</section>

<footer>
<div class="footer-main">
  <div class="footer-left">
    <i class="fas fa-bars"></i>
  </div>
  <div class="footer-right">
    <p>PRODUCTS</p>
    <p>STORES</p>
  </div>
</div>

</footer>
    
  </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" scoped>
.contact{
    width:91.7%;
    max-width: 2000px;
    background-color: #FFF;
    .contact-center{
        display:flex;
        img{
            width:3vw;
        }
    }
    .contact-top{
        display:flex;
        justify-content: center;
    }
    .contact-bottom{
        display:flex;
        justify-content:space-between;
    }
    .contact3 img{
        width:10vw;
    }
    .contact5{
        display:flex;
    }
    .scroll{
        width:10vw;
    }
    .insta{
        width:5vw;
    }
    .facebook{
        width:5vw;
    }
    .twitter{
        width:5vw;
    }
}
.contact-res{
    display:none;
}

.footer-main{
    display:none;
}
@media all and (max-width:900px){
    .contact{
        display:none;
    }
    .contact-res{
        display:block;
        max-width: 900px;
        width:100%;
        background-color: rgba(86, 38, 8, 0.4);
        .contact-main{
            width:30vw;
            margin:0 auto;
        }
        .contact-center{
            display:flex; 
            img{
                width:5vw;
            }
        }
        .contact-image{
            display:flex;
            flex-direction: column;
            .contact-image1{
                width:30vw;
            }
    }
    .contact3 img{
        width:20vw;
    }
    .sns{
        display:flex;
        .insta{
            width:3vw;
        }
        .facebook{
           width:2vw;
        }
       .twitter{
           width:3vw;
       }
    }





    .contact-text{
        display:flex;
    }
    .scroll{
        width:10vw;
    }
    .logo{
        width:30vw;
    }
}
}
   
@media all and (max-width:900px){
    footer{
        max-width: 900px;
        width:100%;
        background: #562608;
    }
    .footer-main{
        display:flex;
    }
    .footer-right{
        display:flex;
    }
}






</style>