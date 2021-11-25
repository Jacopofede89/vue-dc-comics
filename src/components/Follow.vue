<template>
  <section>

    <div class="img_footer">
        <button>SIGN UP NOW!</button>
          <ul>
              <li><img src="assets/img/footer-facebook.png" alt=""></li>
              <li><img src="assets/img/footer-twitter.png" alt=""></li>
              <li><img src="assets/img/footer-youtube.png" alt=""></li>
              <li><img src="assets/img/footer-pinterest.png" alt=""></li>
              <li><img src="assets/img/footer-periscope.png" alt=""></li>
          </ul>

        <span>FOLLOW US</span>
    </div>

  </section>
</template>

<script>
export default {
  name: 'Follow',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    section {
        height: 100px;
        background-color:rgba(48,48,48,255);
        .img_footer {
            width: 80%;
            margin: auto;
        }
        button {
            color: white;
            background-color:rgba(48,48,48,255);
            float: left;
            font-size: 15px;
            padding: 5px;
            border: 2px solid rgba(2,130,249,255);
            margin-top: 20px;
        }
        span {
            float: right;
            margin-right: 20px;
            line-height: 100px;
            color:rgba(2,130,249,255);
            font-weight: bold;
        }
        ul {
            float: right;
            li {
                display: inline-block;
                margin-right: 20px;
                line-height: 120px;
            }
        }
    }
</style>