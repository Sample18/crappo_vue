<template>
  <div class="start-mining-wrapper">
      <div class="start-mining" v-for="(valuta, key) in currencies" :key="key">
        <img :src='valuta.img' alt="btc-logo" width="80" height="80">
        <h3>{{valuta.title}} <i>{{valuta.abbreviation}}</i></h3>
        <p>{{valuta.description}}</p>
        <a class="start" href="">Start mining<img class="img-arrow" src="../assets/pictures/Arrow-Right.svg" width="32" height="32" alt="arrow"></a>
        <a class="start-end" href=""><img src="../assets/pictures/Arrow-Right1.svg" alt="arrow" width="64" height="64"></a>
        </div>
  </div>
</template>

<script>
export default {
  name: "StartMining",
  data () {
    return {
      src: "btc-logo.svg",
      currencies: [
        {
          title: 'Bitcoin',
          abbreviation: 'BTC',
          description: 'Digital currency in which a record of transactions is maintained.',
          img: require("../assets/pictures/btc-logo.svg"),
        },
        {
          title: 'Ethereum',
          abbreviation: 'ETH',
          description: 'Blockchain technology to create and run decentralized digital applications.',
          img: require("../assets/pictures/eth-logo.svg"),
        },
        {
          title: 'Litecoin',
          abbreviation: 'LTC',
          description: 'Cryptocurrency that enables instant payments to anyone in the world.',
          img: require("../assets/pictures/ltc-logo.svg"),
        },
      ],
    }
  }
}
</script>

<style scoped>

.start-mining-wrapper {
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  max-width: 1200px;
  padding-bottom: 100px;
}

.start-mining {
  max-width: 370px;
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 48px;
  border-radius: 16px;
}

.start-mining:hover {
  background-color: rgba(43, 7, 110, 1);
  /*background-filter: blur(250px);*/
}

.start-mining > img {
  margin-bottom: 53px;
}

.start-mining > h3 {
  font-family: "Rubik-Bold", Helvetica, Arial, sans-serif;
  font-size: 32px;
  color: rgba(13, 13, 43, 1);
  margin: 0;
  margin-bottom: 21px;
}

.start-mining:hover h3 {
  color: rgba(255, 255, 255, 1);
}

.start-mining > h3 > i {
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 18px;
  color: rgba(189, 189, 189, 1);
  margin: 0;
  margin-left: 3px;
  font-style: normal;
}

.start-mining:hover h3 > i {
  color: rgba(191, 181, 211, 1);
}

.start-mining > p {
  font-family: "Rubik-Regular", Helvetica, Arial, sans-serif;
  font-size: 16px;
  color: rgba(130, 130, 130, 1);
  margin: 0 2vw;
  margin-bottom: 25px;
  text-align: center;
  line-height: 28px;
}

.start-mining:hover p {
  color: rgba(255, 255, 255, 1);
}

.start-mining > a {
  margin-bottom: 44px;
}

.start {
  display: none;
  background-color: rgba(54, 113, 233, 1);
  padding: 22px 24px;
  padding-right: 72px;
  border-radius: 32px;
  text-decoration: none;
  color: rgba(255, 255, 255, 1);
  font-family: "Rubik-Medium", Helvetica, Arial, sans-serif;
  font-size: 18px;
  position: relative;
}

.start-mining:hover .start {
  display: block;
}

.start-mining:hover .start-end {
  display: none;
}

@media (max-width: 1200px) {
  .start-mining-wrapper {
    justify-content: space-around;
  }
}
</style>