<template>
  <section>
      <div>
          <ul>
              <li v-for="pic, i in pics" :key="i"><img :src="pic.img">{{pic.text}}</li>
          </ul>
      </div>
  </section>
</template>

<script>
export default {
  name: 'Shop',
  data(){
     return {
        pics: [
            {
                img: "../img/buy-comics-digital-comics.png",
                text: "DIGITAL COMICS",
                visible: true
            },
            {
                img: "../img/buy-comics-merchandise.png",
                text: "DC MERCHANDISE",
                visible: false
            },
            {
                img: "../img/buy-comics-shop-locator.png",
                text: "SUBSCRIPTION",
                visible: false
            },
            {
                img: "../img/buy-comics-subscriptions.png",
                text: "COMIC SHOP LOCATOR",
                visible: false
            },
            {
                img: "../img/buy-dc-power-visa.svg",
                text: "DC POWER VISA",
                visible: false
            }
        ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
    margin: 0;
    background-color:rgba(2,130,249,255);
    height: 150px;
    div {
        width: 90%;
        margin:0 auto;
        img {
            padding: 10px;
            color: white;
            width: 50px;
            vertical-align: middle;
        }
        li {
            font-size: 13px;
            color: white;
            display: inline-block;
            margin: 30px;
            font-weight: bold;
        }
    }
}
</style>
