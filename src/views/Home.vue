<template>
  <div>
    <section class="top-section">
      <header>
        <div class="top-logo">
          <img src="../assets/pictures/Logo.svg" width="40" height="40" alt="logo">
          <h3>crappo</h3>
        </div>
        <div class="menu-wrapper">
          <ul class="top-menu">
            <li><a href="">Products</a></li>
            <li><a href="">Features</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Contact</a></li>
          </ul>
          <ul class="top-login">
            <li ><a class="vert-line" href="">Login</a></li>
            <li><a class="register" href="">Register</a></li>
          </ul>
          <pop-up/>
        </div>
      </header>
      <div class="section1">
        <div class="section-h1">
          <p class="sale"><span class="span-wrapper">75% SAVE</span> For the Black Friday weekend</p>
          <h1>Fastest & secure platform to invest in crypto</h1>
          <p class="buysell">Buy and sell cryptocurrencies, trusted by 10M wallets with over $30 billion in transactions.</p>
          <a class="try" href="">Try for FREE<img class="img-arrow" src="../assets/pictures/Arrow-Right.svg" width="32" height="32" alt="arrow"></a>
        </div>
        <div class="section-img">
          <img src="../assets/pictures/Illustration.svg" alt="bgimg">
        </div>
        <img class="palka-bg" src="../assets/pictures/palka.svg" alt="bgimg">
        <img class="palka2-bg" src="../assets/pictures/palka2.svg" alt="bgimg">
      </div>
    </section>
    <section class="section2">
      <div class="statistic">
        <div class="statistic-wrapper st1">
          <img src="../assets/pictures/Icon1.svg" width="80" height="80" alt="icon">
          <div class="statistic-text">
            <h2 class="statistic-h2">$30B</h2>
            <p class="statistic-p">Digital Currency Exchanged</p>
          </div>
        </div>
        <div class="statistic-wrapper st2">
          <img src="../assets/pictures/Icon2.svg" width="80" height="80" alt="icon">
          <div class="statistic-text">
            <h2 class="statistic-h2">10M+</h2>
            <p class="statistic-p">Trusted Wallets Investor</p>
          </div>
        </div>
        <div class="statistic-wrapper st3">
          <img src="../assets/pictures/Icon3.svg" width="80" height="80" alt="icon">
          <div class="statistic-text">
            <h2 class="statistic-h2">195</h2>
            <p class="statistic-p">Countries Supported</p>
          </div>
        </div>
      </div>
      <div class="choose">
        <img class="choose-img" src="../assets/pictures/Illustrations1.svg" alt="illustration" width="650" height="473">
        <div class="choose-text">
          <h2 class="choose-h2">Why you should choose CRAPPO</h2>
          <p class="choose-p">Experience the next generation cryptocurrency platform. No financial borders, extra fees, and fake reviews.</p>
          <a class="choose-a" href="">Learn More</a>
        </div>
        <img class="palka3-bg" src="../assets/pictures/palka3.svg" alt="bgimg">
        <img class="palka4-bg" src="../assets/pictures/palka4.svg" alt="bgimg">
        <img class="palka5-bg" src="../assets/pictures/palka5.svg" alt="bgimg">
      </div>
      <div class="calc-check">
        <h2 class="calc-h2">Check how much you can earn</h2>
        <p class="calc-p">Let’s check your hash rate to see how much you will earn today, Exercitation veniam consequat sunt nostrud amet.</p>
      </div>
      <div class="calc-form">
        <input type="number" name="name" id="hash-rate" required placeholder="Enter your hash rate" class="hash-rate">
        <select name="hash_rate" class="select-hash-rate" id="select-hash-rate">
          <option value="1">MH&#47;s</option>
          <option value="1000">GH&#47;s</option>
          <option value="1000000000">TH&#47;s</option>
        </select>
        <button class="button-hr">Calculate</button>
      </div>
    </section>
    <section class="section3">
      <div class="calc-continued">
        <p class="estimated">ESTIMATED 24 HOUR REVENUE:</p>
        <p class="count">0.055 130 59 ETH <span class="count-bl">(&#36;1275)</span></p>
        <p class="revenue">Revenue will change based on mining difficulty and Ethereum price.</p>
      </div>
      <h2 class="s3-heading">Trade securely and market the high growth cryptocurrencies.</h2>

<!--Компонент с карточками крипты-->
      <StartMining/>
<!--       -->

    </section>
    <section class="section4">
      <h2 class="infrastructure">Market sentiments, portfolio, and run the infrastructure of your choice</h2>
      <div class="invest">
        <div class="invest-wrapper iw1">
          <h3 class="iw-h3">Invest Smart</h3>
          <p>Get full statistic information about the behaviour of buyers and sellers will help you to make the decision.</p>
          <a href="">Learn More</a>
        </div>
        <img src="../assets/pictures/Chart.svg" alt="chart" width="580" height="427">
      </div>
      <div class="detailed">
        <img src="../assets/pictures/Statistic.svg" alt="statistic" width="710" height="453">
        <div class="invest-wrapper iw2">
          <h3 class="iw-h3">Detailed Statistics</h3>
          <p>View all mining related information in realtime, at any point at any location and decide which polls you want to mine in.</p>
          <a href="">Learn More</a>
        </div>
      </div>
      <div class="profit">
        <div class="invest-wrapper iw3">
          <h3 class="iw3-lh iw-h3">Grow your profit and track your investments</h3>
          <p>Use advanced analytical tools. Clear TradingView charts let you track current and historical profit investments.</p>
          <a href="">Learn More</a>
        </div>
        <img src="../assets/pictures/Table.svg" alt="table" width="682" height="334">
      </div>
    </section>
    <section class="section5">
      <div class="join">
        <div class="join-text">
          <h3>Start mining now</h3>
          <p>Join now with CRAPPO to get the latest news and start mining now</p>
        </div>
        <form action="#" method="GET" class="subscribe-form">
          <input type="email" placeholder="Enter your email" class="subscribe-input">
          <button class="subscribe-button">Subscribe</button>
        </form>
        <img src="../assets/pictures/Vector.svg" alt="bgimg" width="160" height="259" class="join-img1">
        <img src="../assets/pictures/Vector1.svg" alt="bgimg" width="140" height="185" class="join-img2">
      </div>
      <img src="../assets/pictures/palka8.svg" alt="bgimg" class="section5-img">
      <img src="../assets/pictures/palka9.svg" alt="bgimg" class="section5-img1">
    </section>
    <footer class="footer">
      <div class="links-wrapper">
        <div class="links">
          <div class="footer-logo">
            <img src="../assets/pictures/Logo.svg" width="40" height="40" alt="logo">
            <h3>crappo</h3>
          </div>
          <ul class="footer-menu fm1">
            <li class="links-menu-heading">Quick Link</li>
            <li class="rows-menu"><a href="" class="links-menu">Home</a></li>
            <li class="rows-menu"><a href="" class="links-menu">Products</a></li>
            <li class="rows-menu"><a href="" class="links-menu">About</a></li>
            <li class="rows-menu"><a href="" class="links-menu">Features</a></li>
            <li class="rows-menu"><a href="" class="links-menu">Contact</a></li>
          </ul>
          <ul class="footer-menu">
            <li class="links-menu-heading">Resources</li>
            <li class="rows-menu"><a href="" class="links-menu">Download Whitepapper</a></li>
            <li class="rows-menu"><a href="" class="links-menu">Smart Token</a></li>
            <li class="rows-menu"><a href="" class="links-menu">Blockchain Explorer</a></li>
            <li class="rows-menu"><a href="" class="links-menu">Crypto API</a></li>
            <li class="rows-menu"><a href="" class="links-menu">Interest</a></li>
          </ul>
        </div>
        <div class="payment">
          <h2>We accept following payment systems</h2>
          <div class="payment-img">
            <img src="../assets/pictures/Visa.svg" alt="visa" width="96" height="64">
            <img src="../assets/pictures/Mastercard.svg" alt="mastercard" width="96" height="64">
            <img src="../assets/pictures/Bitcoin.svg" alt="bitcoin" width="96" height="64">
          </div>
        </div>
      </div>
      <div class="resources">
        <p>&#169;2021 CRAPPO. All rights reserved</p>
        <div class="resources-img">
          <a href=""><img src="../assets/pictures/facebook.svg" alt="facebook" width="24" height="24"></a>
          <a href=""><img src="../assets/pictures/instagram.svg" alt="instagram" width="24" height="24"></a>
          <a href=""><img src="../assets/pictures/youtube.svg" alt="youtube" width="24" height="24"></a>
          <a href=""><img src="../assets/pictures/twitter.svg" alt="twitter" width="24" height="24"></a>
          <a href=""><img src="../assets/pictures/linkedin.svg" alt="linkedin" width="24" height="24"></a>
        </div>
      </div>
    </footer>
  </div>
</template>

<style>
@font-face {
  src: url('../assets/fonts/Inter-Bold.ttf');
  font-family: "Inter-Bold";
}

@font-face {
  src: url('../assets/fonts/Rubik-Regular.ttf');
  font-family: "Rubik-Regular";
}

@font-face {
  src: url('../assets/fonts/Rubik-Medium.ttf');
  font-family: "Rubik-Medium";
}

@font-face {
  src: url('../assets/fonts/Rubik-Bold.ttf');
  font-family: "Rubik-Bold";
}

body {
  margin: 0;
}

header {
  margin: 0 auto 51px auto;
  display: flex;
  max-width: 1200px;
  min-height: 54px
}

.top-section {
  margin: 0 auto;
  padding-top: 58px;
  padding-bottom: 197px;
  background-color: rgb(13, 13, 43);
}

@media (max-width: 1215px) {
  .top-section {
    padding-right: 2vw;
    padding-left: 2vw;
  }
}

.top-logo {
  display: flex;
  max-width: 136px;
  padding-top: 8px;
}

.top-logo > h3 {
  color: rgba(255, 255, 255, 1);
  font-family: "Inter-Bold", Helvetica, Arial, sans-serif;
  text-transform: uppercase;
  margin: 0;
  margin-top: 9px;
  margin-left: 16px;
}

.menu-wrapper {
  margin-left: auto;
  display: flex;
  flex-wrap: wrap;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.top-menu {
  display: flex;
  min-height: 100%;
}

.top-menu > li {
  display: flex;
}

.top-login {
  display: flex;
  min-height: 100%;
}

.top-login > li {
  display: flex;
}

.top-menu > li > a {
  display: flex;
  align-items: center;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  padding: 0 18px;
}

.vert-line,
.register {
  display: flex;
  align-items: center;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  padding: 0 30px;
}

.vert-line::after {
  content: " ";
  background-color: rgba(196, 196, 196, 1);
  width: 1px;
  height: 24px;
  margin-left: 20px;
}

.register {
  background-color: rgba(54, 113, 233, 1);
  border-radius: 32px;
}

@media (max-width: 530px) {
  .top-menu,
  .top-login {
    display: none;
  }
}

.section1 {
  position: relative;
  margin: 0 auto;
  max-width: 1200px;
  display: flex;
}

.section-h1 {
  width: 50%;
}

.section-h1 > p {
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  color: rgba(255, 255, 255, 1);
}

.sale {
  margin: 0;
  margin-top: 79px;
  margin-bottom: 25px;
  padding: 11px;
  padding-left: 5px;
  background-color: rgba(255, 255, 255, 0.1);
  border-radius: 32px;
  width: 349px;
}

.span-wrapper {
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  color: rgba(13, 13, 43, 1);
  background-color: rgba(255, 255, 255, 1);
  padding: 6px 19px;
  border-radius: 32px;
  margin-right: 11px;
}

.section-h1 > h1 {
  margin: 0;
  margin-bottom: 23px;
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 64px;
  color: rgba(255, 255, 255, 1);
}

.buysell {
  margin: 0;
  line-height: 27px;
  max-width: 430px;
  margin-bottom: 56px;
}

.try {
  background-color: rgba(54, 113, 233, 1);
  padding: 22px 24px;
  padding-right: 72px;
  border-radius: 32px;
  text-decoration: none;
  color: rgba(255, 255, 255, 1);
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 18px;
  position: relative;
  z-index: 1;
}

.section-img {
  width: 50%;
}

.section-img img {
  width: 100%;
}

@media (max-width: 782px) {
  .section1 {
    flex-direction: column;
  }
  .section-img {
    width: 100%;
  }
  .section-h1 {
    width: 100%;
  }
  .section-h1 h1,
  .buysell {
    overflow-wrap: break-word;
  }
}

.img-arrow {
  position: absolute;
  right: 15px;
  top: 16px;
}

.palka-bg {
  position: absolute;
  bottom: -289px;
}

.palka2-bg {
  position: absolute;
  right: -118px;
  bottom: -98px;
}

@media (min-width: 683px) and (max-width: 1000px) {
  .palka2-bg {
    display: none;
  }
}

@media (max-width: 682px) {
  .palka-bg {
    display: none;
  }
}

.section2 {
  margin: 0 auto;
  background-color: rgb(13, 13, 43);
  position: relative;
}

@media (max-width: 1215px) {
  .section2 {
    padding-right: 2vw;
    padding-left: 2vw;
  }
}

.statistic {
  max-width: 1440px;
  display: flex;
  margin: 0 auto;
  margin-bottom: 106px;
}

.statistic-wrapper {
  display: flex;
  margin: 0;
}

.st1 {
  margin-right: auto;
  margin-left: 120px;
}

.st2 {
  margin-right: 29px;
}

.st3 {
  margin-right: 194px;
  margin-left: auto;
}

.statistic-text {
  margin-left: 25px;
}

.statistic-h2 {
  margin: 0;
  margin-top: 7px;
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 40px;
  color: rgba(255, 255, 255, 1);
}

.statistic-p {
  margin: 0;
  margin-top: 14px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  color: rgba(255, 255, 255, 1);
}

@media (max-width: 1200px) {
  .statistic {
    flex-wrap: wrap;
  }
  .st1 {
    margin-left: 0;
  }
  .st2 {
    margin-right: 0;
  }
  .st3 {
    margin-left: inherit;
    margin-right: 0;
  }
}

@media (max-width: 910px) {
  .st3 {
    margin-left: 0;
    margin-right: 0;
  }
}

.choose {
  position: relative;
  display: flex;
  max-width: 1200px;
  margin: 0 auto;
  margin-bottom: 206px;
}

.choose-img {
  width: 50%;
}

.choose-text {
  margin-left: 71px;
  margin-top: 77px;
}

.choose-h2 {
  margin: 0;
  margin-bottom: 23px;
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 40px;
  color: rgba(255, 255, 255, 1);
  line-height: 60px;
}

.choose-p {
  margin: 0;
  margin-bottom: 51px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  color: rgba(255, 255, 255, 1);
  line-height: 28px;
  max-width: 400px;
}

.choose-a {
  background-color: rgba(54, 113, 233, 1);
  padding: 19px 24px;
  border-radius: 32px;
  text-decoration: none;
  color: rgba(255, 255, 255, 1);
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 18px;
}

@media (max-width: 1151px) {
  .choose-img {
    width: 50%;
  }
  .choose-text {
    width: 50%;
  }
}

@media (max-width: 782px) {
  .choose {
    flex-direction: column-reverse;
  }
  .choose-img {
    width: 100%;
  }
  .choose-text {
    margin-left: inherit;
    width: 100%;
  }
}
.palka3-bg {
  position: absolute;
  left: -118px;
  bottom: -98px;
}

.palka4-bg {
  position: absolute;
  right: -121px;
  top: -127px;
}

.palka5-bg {
  position: absolute;
  right: -123px;
  bottom: -33px;
}

@media (max-width: 1300px) {
  .palka4-bg {
    right: 0;
  }
  .palka5-bg {
    right: 0;
  }
}

.calc-check {
  margin: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 63px;
}

.calc-h2 {
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 40px;
  color: rgba(255, 255, 255, 1);
  margin: 0;
  margin-bottom: 31px;
}

.calc-p {
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 18px;
  color: rgba(224, 224, 224, 1);
  max-width: 600px;
  margin: 0;
  text-align: center;
  line-height: 27px;
}

.calc-form {
  max-width: 942px;
  background-color: rgba(251, 252, 254, 1);
  padding-top: 49px;
  padding-bottom: 46px;
  margin: 0 auto;
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
}

.hash-rate {
  outline: none;
  border-top: none;
  border-left: none;
  border-right: none;
  border-bottom-width: 1px;
  padding-bottom: 9px;
  border-color: rgba(196, 196, 196, 1);
  background-color:transparent;
  box-shadow: none;
  width: 403px;
  margin-left: 47px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 20px;
  color: rgba(13, 13, 43, 1);
}

.select-hash-rate {
  outline: none;
  -moz-appearance: none;
  -webkit-appearance: none;
  border-top: none;
  border-left: none;
  border-right: none;
  border-bottom-width: 1px;
  padding-bottom: 10px;
  border-color: rgba(196, 196, 196, 1);
  background-color:transparent;
  box-shadow: none;
  width: 200px;
  margin-left: 50px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 20px;
  color: rgba(13, 13, 43, 1);
}

.button-hr {
  background-color: rgba(54, 113, 233, 1);
  padding: 19px 32px;
  margin-left: 37px;
  border-radius: 32px;
  border: none;
  color: rgba(255, 255, 255, 1);
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 18px;
}

.calc-continued {
  max-width: 942px;
  padding-top: 50px;
  margin: 0 auto;
  margin-bottom: 100px;
  background-color: rgba(255, 255, 255, 1);
  border-bottom-left-radius: 20px;
  border-bottom-right-radius: 20px;
}

.estimated {
  margin: 0;
  margin-left: 49px;
  margin-bottom: 25px;
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 16px;
  color: rgba(54, 113, 233, 1);
}

.count {
  margin: 0;
  margin-left: 49px;
  margin-bottom: 11px;
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 32px;
  color: rgba(13, 13, 43, 1);
}

.count-bl {
  color: rgba(54, 113, 233, 1);
}

.revenue {
  margin: 0;
  margin-left: 49px;
  padding-bottom: 54px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 16px;
  color: rgba(130, 130, 130, 1);
}

@media (max-width: 1000px) {
  .button-hr {
    margin-right: 47px;
  }
  .hash-rate {
    width: 300px;
  }
}

@media (max-width: 890px) {
  .select-hash-rate {
    width: 100px;
  }
}

@media (max-width: 786px) {
  .hash-rate {
    width: 210px;
  }
}

@media (max-width: 691px) {
  .button-hr {
    margin-top: 33px;
  }
  .select-hash-rate {
    margin-right: 47px;
    margin-top: 33px;
  }
}

.section3 {
  margin: 0 auto;
  background-color: rgba(248, 249, 251, 1);
}

@media (max-width: 1215px) {
  .section3 {
    padding-right: 2vw;
    padding-left: 2vw;
  }
}

.s3-heading {
  text-align: center;
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 40px;
  color: rgba(13, 13, 43, 1);
  margin: 0 auto;
  margin-bottom: 63px;
  max-width: 740px;
  line-height: 60px;
}

.section4 {
  margin: 0 auto;
  padding-top: 100px;
  padding-bottom: 119px;
  background-color: rgba(43, 7, 110, 1);
}

@media (max-width: 1440px) {
  .section4 {
    padding-right: 2vw;
    padding-left: 2vw;
  }
}

.infrastructure {
  margin: 0 auto;
  margin-bottom: 99px;
  text-align: center;
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 40px;
  color: rgba(255, 255, 255, 1);
  max-width: 758px;
  line-height: 61px;
}

.invest {
  display: flex;
  max-width: 1440px;
  box-sizing: border-box;
  padding-left: 120px;
  padding-right: 186px;
  margin: 0 auto;
  margin-bottom: 119px;
}

.detailed {
  display: flex;
  max-width: 1440px;
  margin: 0 auto;
  margin-bottom: 100px;
}

.profit {
  display: flex;
  max-width: 1440px;
  box-sizing: border-box;
  margin: 0 auto;
  padding-left: 121px;
}


.iw1 {
  margin-right: 146px;
  margin-top: 44px;
}

.iw2 {
  margin-left: 91px;
  margin-top: 110px;
}

.iw3 {
  margin-top: 29px;
}

.iw-h3 {
  margin: 0;
  margin-bottom: 29px;
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 32px;
  color: rgba(255, 255, 255, 1);
  max-width: 454px;
}

.iw3-lh {
  line-height: 49px;
  margin-bottom: 24px;
}

.invest-wrapper p {
  margin: 0;
  margin-bottom: 51px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 16px;
  color: rgba(224, 224, 224, 1);
  line-height: 28px;
  max-width: 408px;
}

.invest-wrapper a {
  margin: 0;
  background-color: rgba(54, 113, 233, 1);
  padding: 19px 33px;
  padding-right: 32px;
  border-radius: 32px;
  text-decoration: none;
  color: rgba(255, 255, 255, 1);
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 18px;
}

@media (max-width: 1440px) {
  .invest,
  .detailed,
  .profit {
    justify-content: space-between;
    padding-left: inherit;
    padding-right: inherit
  }
  .invest img,
  .detailed img,
  .profit img {
    width: 50%;
  }
  .invest-wrapper {
    width: 50%;
  }
  .iw1 {
    margin-right: 10px;
  }
}

@media (max-width: 1100px) {
  .detailed {
    flex-direction: column-reverse;
  }
  .invest,
  .profit {
    flex-direction: column;

  }
  .invest img,
  .detailed img,
  .profit img {
    width: 100%;
  }
  .invest-wrapper {
    width: 100%;
    margin-bottom: 60px;
    margin-left: inherit;
  }
}


.section5 {
  position: relative;
  margin: 0 auto;
  padding-top: 89px;
  padding-bottom: 88px;
  background: linear-gradient(#2B076E, #0D0D2B);
}

@media (max-width: 1440px) {
  .section5 {
    padding-right: 2vw;
    padding-left: 2vw;
  }
}

.join {
  max-width: 1200px;
  margin: 0 auto;
  padding-top: 53px;
  background-color: rgba(54, 113, 233, 1);
  display: flex;
  border-radius: 16px;
  position: relative;
}

.join-text {
  margin-left: 50px;
  margin-right: 142px;
}

.join-text h3 {
  margin: 0;
  margin-bottom: 20px;
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 32px;
  color: rgba(255, 255, 255, 1);
  max-width: 501px;
}

.join-text p {
  margin: 0;
  margin-bottom: 49px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 16px;
  color: rgba(255, 255, 255, 1);
  max-width: 348px;
  line-height: 28px;
}

.join-img1 {
  position: absolute;
  top: -23px;
  left: 23px;
  object-fit: contain;
}

.join-img2 {
  position: absolute;
  bottom: -26px;
  right: 15px;
  object-fit: contain;
}

.subscribe-form {
  margin: 0;
  margin-top: 16px;
  z-index: 1;
}

.subscribe-input {
  outline: none;
  border-top: none;
  border-left: none;
  border-right: none;
  border-bottom-width: 1px;
  padding-bottom: 9px;
  border-color: rgba(255, 255, 255, 1);
  background-color: transparent;
  box-shadow: none;
  width: 370px;
  margin-left: 47px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 16px;
  color: rgba(255, 255, 255, 1);
}

.subscribe-button {
  background-color: rgba(255, 255, 255, 1);
  padding: 17px 32px;
  margin-left: 37px;
  border-radius: 32px;
  border: none;
  color: rgba(13, 13, 43, 1);
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 18px;
}

.section5-img {
  position: absolute;
  bottom: 0;
  left: 48px;
}

.section5-img1 {
  position: absolute;
  bottom: 0;
  left: 406px;
}

@media (max-width: 1250px) {
  .join-text {
    margin-right: 0;
  }
  .subscribe-form {
    margin-right: 50px;
  }
}

@media (max-width: 1122px) {
  .subscribe-input {
    width: 200px;
  }
  .subscribe-button {
    margin-top: 30px;
  }
}

@media (max-width: 600px) {
  .join {
    flex-direction: column;
  }
  .join-text p {
    margin: 0;
  }
  .subscribe-form	{
    margin: 16px;
  }
}

.footer {
  margin: 0;
  padding-top: 79px;
  background-color: rgba(13, 13, 43, 1);
}

@media (max-width: 1440px) {
  .footer {
    padding-right: 2vw;
    padding-left: 2vw;
  }
}

.links-wrapper {
  display: flex;
  max-width: 1440px;
  margin: 0 auto;
  margin-bottom: 115px;
}

.links {
  display: flex;
  margin-left: 121px;
  margin-right: 132px;
}

.footer-logo {
  display: flex;
  margin-right: 171px;
}

.footer-logo > h3 {
  color: rgba(255, 255, 255, 1);
  font-family: "Inter-Bold", Helvetica, Arial, sans-serif;
  text-transform: uppercase;
  margin: 0;
  margin-top: 9px;
  margin-left: 16px;
}

.footer-menu {
  margin-top: 5px;
}

.fm1 {
  margin-right: 146px;
}

.links-menu-heading {
  margin-bottom: 37px;
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 18px;
  color: rgba(255, 255, 255, 1);
}

.rows-menu {
  margin-bottom: 19px;
}

.links-menu {
  color: rgba(242, 242, 242, 1);
  text-decoration: none;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 16px;
}

.payment h2 {
  margin: 0;
  margin-bottom: 41px;
  max-width: 355px;
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 32px;
  line-height: 150%;
  color: rgba(255, 255, 255, 1);
}

.payment img {
  margin-right: 20px;
}

.resources {
  display: flex;
  max-width: 1440px;
  margin: 0 auto;
  padding-bottom: 78px;
}

.resources p {
  margin: 0;
  margin-left: 121px;
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 16px;
  color: rgba(255, 255, 255, 1);
}

.resources-img {
  margin-left: auto;
  margin-right: 89px;
  margin-top: -2px;
}

.resources-img a {
  margin-right: 30px;
}

@media (max-width: 1220px) {
  .links {
    margin-left: inherit;
  }
}

@media (max-width: 1000px) {
  .links {
    display: none;
  }
  .resources p {
    margin-left: inherit;
  }
  .resources-img {
    margin-right: inherit;
  }
}
</style>

<script>

import StartMining from "@/components/StartMining";
import popUp from "@/components/popUp";

export default {
  name: 'Home',
  components: {
    StartMining,
    popUp,
  },
}
</script>
