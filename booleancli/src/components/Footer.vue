<template>
<div class="footer-container">
<div class="nav-blue">
    <ul class="nav_ul">
        <li class="nav_li" v-for="(link, i) in shopItem" :key="i">
          <img class="nav_icon" :src="link.src" :alt="link.text" />
          <a :href="link.href" class="nav_link">
            <p>{{ link.text }}</p>
          </a>
       </li>
    </ul>
</div>
<div class="herobg_footer">
    <div class="hero_container">
        <div class="right_side">
            <div class="col-1_6 size-col">
                    <h3 class="list-title">DC COMICS</h3>
                    <ul class="foot-li">
                        <li><a class="list-foot" href="#">Characters</a></li>
                        <li><a class="list-foot" href="#">Comics</a></li>
                        <li><a class="list-foot" href="#">Movie</a></li>
                        <li><a class="list-foot" href="#">TV</a></li>
                        <li><a class="list-foot" href="#">Games</a></li>
                        <li><a class="list-foot" href="#">Videos</a></li>
                        <li><a class="list-foot" href="#">New</a></li>
                    </ul>
                    <h3 class="list-title">SHOP</h3>
                    <ul class="foot-li">
                        <li><a class="list-foot" href="#">Shop DC</a></li>
                        <li><a class="list-foot" href="#">Shop CD Collectibles</a></li>
                    </ul>
              </div>

                <div class="col-1_6 size-col">
                    <h3 class="list-title">DC</h3>
                    <ul class="foot-li">
                        <li><a class="list-foot" href="#">Term Of Use</a></li>
                        <li><a class="list-foot" href="#">Privacy policy(New)</a></li>
                        <li><a class="list-foot" href="#">Ad Choice</a></li>
                        <li><a class="list-foot" href="#">Advertising</a></li>
                        <li><a class="list-foot" href="#">Jobs</a></li>
                        <li><a class="list-foot" href="#">Subscriptions</a></li>
                        <li><a class="list-foot" href="#">Talent Workshops</a></li>
                        <li><a class="list-foot" href="#">CPSC Certificates</a></li>
                        <li><a class="list-foot" href="#">Ratings</a></li>
                        <li><a class="list-foot" href="#">Shop Help</a></li>
                        <li><a class="list-foot" href="#">Contact Us</a></li>
                    </ul>
                </div>

                <div class="col-1_6 size-col">
                    <h3 class="list-title">SITES</h3>
                    <ul class="foot-li">
                        <li><a class="list-foot" href="#">DC</a></li>
                        <li><a class="list-foot" href="#">MAD Magazine</a></li>
                        <li><a class="list-foot" href="#">DC Kids</a></li>
                        <li><a class="list-foot" href="#">DC Universe</a></li>
                        <li><a class="list-foot" href="#">DC Power Visa</a></li>
                    </ul>
                </div>

        </div>
        <div class="left_side">
            <div>
             <img class="dc_footer_logo" src="../assets/img/dc-logo-bg.png">
             </div>
        </div>
    </div>
</div>
<div class="background-enter">
      <div class="container-enter">
        <div>
          <button class="button-footer">SIGN_UP NOW!</button>
        </div>
        <div class="social-icon">
          <h2>Follow Us</h2>
          <img src="../assets/img/footer-facebook.png" alt="Icon">
          <img src="../assets/img/footer-twitter.png" alt="Icon">
          <img src="../assets/img/footer-youtube.png" alt="Icon">
          <img src="../assets/img/footer-pinterest.png" alt="Icon">
          <img src="../assets/img/footer-periscope.png" alt="Icon">
        </div>
      </div>
    </div>

</div>

</template>

<script>
 export default {
     name: "Footer",

     data(){
         return{
             shopItem:[
                {
                src: require("../assets/img/buy-comics-digital-comics.png"),
                text: "digital comics",
                href: "#",
                },
                {
                 src: require("../assets/img/buy-comics-merchandise.png"),
                 text: "digital merchandise",
                 href: "#",
               },
               {
                 src: require("../assets/img/buy-comics-subscriptions.png"),
                 text: "subscriptions",
                 href: "#",
               },
               {
                 src: require("../assets/img/buy-comics-shop-locator.png"),
                 text: "comic shop locator",
                 href: "#",
               },
               {
                 src: require("../assets/img/buy-dc-power-visa.svg"),
                 text: "dc power visa",
                 href: "#",
               },
             ]
         }
     }
 }
</script>