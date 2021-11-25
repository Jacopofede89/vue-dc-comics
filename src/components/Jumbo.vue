<template>
  <header>
      <section>
          <img src="assets/img/jumbotron.jpg" alt="">
      </section>
      
  </header>
</template>

<script>
export default {
  name: 'Jumbo',
 
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
    img{
        object-position: top;
        object-fit: cover;
        width: 100%;
        height: 300px;
        display: block;
    }
    
    
}
    
</style>