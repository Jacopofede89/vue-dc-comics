<template>
  <header>
      <section>
          <img src="assets/img/dc-logo.png" alt="">

        <ul>
            <li v-for="nav, i in navs" :key="i" :class="nav.visible === true ? 'active' : ''">{{nav.text}}</li>
        </ul>
      </section>
      
  </header>
</template>

<script>
export default {
  name: 'Header',
 data(){
     return {
         navs: [
             {
                 text: "Characters",
                 visible: false
             },
             {
                 text: "Comics",
                 visible: true
             },
             {
                 text: "Movies",
                 visible: false
             },
             {
                 text: "TV",
                 visible: false
             },
             {
                 text: "Games",
                 visible: false
             },
             {
                 text: "Collectibles",
                 visible: false
             },
             {
                 text: "Videos",
                 visible: false
             },
             {
                 text: "Fans",
                 visible: false
             },
             {
                 text: "News",
                 visible: false
             },
             {
                 text: "Shop",
                 visible: false
             }
         ]
     }
 }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
    height: 120px;
    section {
        width: 80%;
        margin: auto;
        img {
        float: left;
        margin-top: 30px;
        width: 80px;
        }
        ul {
            float: right;
            li {
                display: inline-block;
                margin: 0 10px;
                margin-top: 60px;
                text-transform: uppercase;
                font-size: 12px;
                font-weight: bold;
                &:hover {
                    background-color: blue;
                    cursor: pointer;
                }
                &.active{
                    color: blue;
                    padding-bottom: 40px;
                    border-bottom: 5px solid blue;
                }
            }
        }
    }
    
    
}
    
</style>
