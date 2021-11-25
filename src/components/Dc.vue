<template>
  <section>
        <div class="main">

            <div class="link">

                <div>
                    <ul>
                        <li v-for="link, i in links" :key="i" :class="link.visible === true ? 'title' : ''">{{link.text}}</li>

                        <!-- <li class="title">DC COMICS</li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                        <li class="title">SHOP</li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li> -->
                    </ul>
                </div>

                <div>
                    <ul>
                        <li v-for="nav, i in navs" :key="i" :class="nav.visible === true ? 'title' : ''">{{nav.text}}</li>

                        <!-- <li class="title">DC</li>
                        <li>Terms Of Use</li>
                        <li>Privacy Policy (New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li> -->
                    </ul>
                </div>

                <div>
                    <ul>
                        <li v-for="site, i in sites" :key="i" :class="site.visible === true ? 'title' : ''">{{site.text}}</li>

                        <!-- <li class="title">SITES</li>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li> -->
                    </ul>
                </div>
            </div>

            <div class="logo_img">

                <img src="assets/img/dc-logo-bg.png" alt="">

            </div>

        </div>
      
  </section>
</template>

<script>
export default {
  name: 'Dc',
  data(){
     return {
         links: [
             {
                 text: "DC COMICS",
                 visible: true
             },
             {
                 text: "Characters",
                 visible: false
             },
             {
                 text: "Comics",
                 visible: false
             },
             {
                 text: "Movies",
                 visible: false
             },
             {
                 text: "Tv",
                 visible: false
             },
             {
                 text: "Games",
                 visible: false
             },
             {
                 text: "Videos",
                 visible: false
             },
             {
                 text: "SHOP",
                 visible: true
             },
             {
                 text: "Shop DC",
                 visible: false
             },
             {
                 text: "Shop DC Collectibles",
                 visible: false
             },
         ],
         navs: [
             {
                 text: "DC",
                 visible: true
             },
             {
                 text: "Terms Of Use",
                 visible: false
             },
             {
                 text: "Privacy Policy (New)",
                 visible: false
             },
             {
                 text: "Ad Choices",
                 visible: false
             },
             {
                 text: "Advertising",
                 visible: false
             },
             {
                 text: "Jobs",
                 visible: false
             },
             {
                 text: "Subscriptions",
                 visible: false
             },
             {
                 text: "Talent Workshops",
                 visible: false
             },
             {
                 text: "PSC Certificates",
                 visible: false
             },
             {
                 text: "Ratings",
                 visible: false
             },
             {
                 text: "Shop Help",
                 visible: false
             },
             {
                 text: "Contact Us",
                 visible: false
             }
         ],
         sites: [
             {
                 text: "SITES",
                 visible: true
             },
             {
                 text: "DC",
                 visible: false
             },
             {
                 text: "MAD Magazine",
                 visible: false
             },
             {
                 text: "DC Universe",
                 visible: false
             },
             {
                 text: "DC Power Visa",
                 visible: false
             },
             
             ],
             
    }
    
 },
    
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    section {
        height: 300px;
        background-image: url("../../public/assets/img/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        .main {
            width: 80%;
            margin: auto;
            .logo_img img {
                height: 300px;
                width: 600px;
                object-fit: none;
                
            }
            .link{
                float: left;
                display: flex;
                flex-wrap: wrap;
                .title {
                    color: white;
                    font-size: 20px;


                }
                li {
                text-align: start;    
                list-style-type: none;
                font-size: 10px;
                color:grey;
                margin-top: 5px;
                text-transform: uppercase;
                }
                ul {
                margin-top: 20px;
                }
            }
            
        }
    }
    
</style>