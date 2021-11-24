<template>
  <section>
        <div class="main">

            <div class="link">

                <div>
                    <ul>
                        <li class="title">DC COMICS</li>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                        <li class="title">SHOP</li>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>

                <div>
                    <ul>
                        <li class="title">DC</li>
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
                        <li>Contact Us</li>
                    </ul>
                </div>

                <div>
                    <ul>
                        <li class="title">SITES</li>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
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
                }
                ul {
                margin-top: 20px;
                }
            }
            
        }
    }
    
</style>